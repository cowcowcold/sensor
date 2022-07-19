1、图片：connect页：节点一识别的图片：项目目录下：/images/object_1.jpg
               index页：图片:/images/tank.jpg
2、txt文件：index页：声音识别结果：/txt/sound_result.txt  格式：{"data_type":"inference_data","data":{"big":0.00,"medium":0.00,"no":0.94,"small":0.00}}
                                  震动识别结果：/txt/wave_result.txt  格式：{"data_type":"inference_data","data":{"big":0.00,"medium":0.00,"no":0.94,"small":0.00}}
                                  图片识别结果： /txt/pic_result.txt  格式：{"data_type":"inference_data","data":{"big":0.00,"medium":0.00,"no":0.94,"small":0.00}}
                                  超声识别结果： /txt/ultasonic_result.txt  格式：{"distance":1000m}
                                  综合识别结果：/txt/all_result.txt  格式：{"data_type":"inference_data","data":{"big":0.00,"medium":0.00,"no":0.94,"small":0.00},"num":"no"}
                                  震动数据：/txt/wave_2.txt 格式：[1,2,165]
                                  声音数据：/txt/sound_2.txt 格式如上
                                  节点数：/txt/bool.txt true/false


/////////////////////07101722更新
              去掉wave_2、sound_2，合并为sound_and_wave_2.txt 格式：{"sound":[12,2,45],"shock":[21,6,965]}
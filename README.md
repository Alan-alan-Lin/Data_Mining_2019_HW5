# Data_Mining_2019_HW5
1.先進行讀檔，再將radius_mean及area_mean切為feature，diagnosis切為target  
![img]https://github.com/Alan-alan-Lin/Data_Mining_2019_HW5/blob/main/HW_5/PY_1.jpg  
2.用cluster.Means設n_clusters=2  
![img]https://github.com/Alan-alan-Lin/Data_Mining_2019_HW5/blob/main/HW_5/PY_2.jpg  
3.用fit_predict對feature進行分類  
![img]https://github.com/Alan-alan-Lin/Data_Mining_2019_HW5/blob/main/HW_5/PY_3.jpg  
4.使用matplotlib中的scatter畫圖，x軸設為radius_mean，y軸設為area_mean，c設為分群結果，印出分類圖形  
![img]https://github.com/Alan-alan-Lin/Data_Mining_2019_HW5/blob/main/HW_5/PY_4.jpg  
5.移除 area_mean 中大於 2000 的資料，從圖中可看出在180,212,352和461行，再利用 drop 把這四筆資料刪除。 
![img]https://github.com/Alan-alan-Lin/Data_Mining_2019_HW5/blob/main/HW_5/PY_5_1.jpg  
![img]https://github.com/Alan-alan-Lin/Data_Mining_2019_HW5/blob/main/HW_5/PY_5_2.jpg   
6.最後將刪除後的結果以圖呈現  
![img]https://github.com/Alan-alan-Lin/Data_Mining_2019_HW5/blob/main/HW_5/PY_6.jpg  

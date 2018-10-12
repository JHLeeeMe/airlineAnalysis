# airlineAnalysis
zeppelin-notebook위에서 spark을 활용한 mapReduce작업 및 시각화

spark (on yarn), hdfs, zeppelin-notebook



## 1. hadoop2 실행

![start_hadoop](https://user-images.githubusercontent.com/35649392/46604002-c5f6fe00-cb2f-11e8-9c28-96dfd7d0c387.png)

## 2. zeppelin 실행, port 8888

![zeppelin-daemon sh_start](https://user-images.githubusercontent.com/35649392/46604001-c55e6780-cb2f-11e8-8ea8-8582cfa91fd1.png)

## 3. zeppelin-notebook위에서 spark을 활용한 mapReduce작업 (read & write CSV)

![zeppelin_0](https://user-images.githubusercontent.com/35649392/46274173-7e9ec980-c593-11e8-94df-1a3057401500.png)

![zeppelin_1](https://user-images.githubusercontent.com/35649392/46274174-7e9ec980-c593-11e8-87e3-8e2e77bc0414.png)

## 4. spark으로 작업한 csv file

![hdfs_cat_csv](https://user-images.githubusercontent.com/35649392/46604003-c5f6fe00-cb2f-11e8-81cb-7499b5faab07.png)

## 5. sql문으로 간단한 시각화

![zeppelin_2](https://user-images.githubusercontent.com/35649392/46274175-7e9ec980-c593-11e8-9983-ba555b5e02e3.png)
demerit값은 늦게 or 빠르게 출발한 수치의 절댓값으로 계산했다.  
운항수에 비례해서 sumDemerit(벌점의 총합)은 오르지만 (좌측표)  
sumDemerit / 운항수 를 보면 제시간이 출발하는 항공사들을 어느정도 파악 가능 (우측표)

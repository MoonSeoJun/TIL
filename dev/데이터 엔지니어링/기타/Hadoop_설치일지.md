# Hadoop 설치일지

# Window 11에서 시도

처음에는 윈도우 환경에서 설치해보려고 시도

하지만 권한과 환경 변수 이슈로 어려움을 겪고 결국 해결하지 못함

</br>

# WSL Ubuntu로 변경

윈도우 환경에서 개발 환경을 구축하는 것은 어렵다고 판단

WSL Ubuntu를 사용하여 리눅스 환경에서 시도하기로 결정

https://buildabetterworld.tistory.com/158

위 블로그를 참고하여 Hadoop 설치 완료

</br>

# 환경 설정 관련

## 설정 파일

- core-site.xml : 클러스터 내 네임노드에서 실행되는 하둡 데몬에 관한 설정
- hdfs-site.xml : 하둡 파일시스템에 관한 설정
- yarn-site.xml : Resourece Manager에 관한 설정
- mapred-site.xml : 맵리듀스에 관한 설정
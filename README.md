# Using the os module in Python

## 개요
- 파일명 : File_control.py

폴더 생성, 파일 생성, 파일 이름 변경, 파일 삭제, 폴더 삭제를 진행하였습니다.

Yolo V5 학습데이터 이용 시 빠르게 파일 처리를 하기 위해 만들어 보았습니다.

OS모듈 사용한 내용이며, 기초적인 내용입니다.

## 설명
    1. 메인 폴더 생성
    2. 메인 폴더 속 폴더 생성(ex: 5개)
    3. 파일 100개 생성(2번 폴더 속)
    4. 생성한 파일 100개의 이름 변경
    5. 생성한 파일 100개 중 50개 삭제
    6. 삭제 전 파일 수 체크, 삭제 후 파일 수 체크 (정말 삭제되었는지 확인)
    7. 파일 다 지우기(테스트 끝)
    8. 폴더 지우기(파일을 다 지운 폴더를 지우기)


위와 같이 한 이유는

학습데이터는 녹화한 동영상에서 프레임별로 jpg로 저장하였고, 해당 jpg에서 모든걸 다 쓰면 많기 때문에, 반을 지운다.

반을 지울때. enumerate로 번호를 매긴 것 중 %2로 True 혹은 False로 선택해서 지운다.

이름을 변경한 이유는 나중에 다 합쳐서 사용하려고 한다.

## 작성자의 말

- 코드를 깔끔하게 정리하지 못하였음.
- 파일 전체로 실행시키지 말것.
- 읽어보고 사용하기.
- 정리 잘하자.!
- 자주 깃허브 올리기!
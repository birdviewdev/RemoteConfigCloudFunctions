# RemoteConfigCloudFunctions
앱 실시간 리모트 컨피그 업데이트를 위한 CloudFunctions

원격 구성 실시간 전파를 위한 과정을 보겠습니다.
-개발자가 Remote Config를 변경  
-Remote Config 변경 트리거를 Cloud Function이 캐치  
-Cloud Function에서 화해 앱 유저에게 silent push 전송  
-silent push를 전달 받은 유저들은 앱 재실행 시 Remote Config 최신 상태를 내려 받음  

위 과정 중 Cloud Function을 Firebase에 업로드 해야하는데 해당 Repository 코드를 업로드 합니다.

참고자료
-CLI (https://firebase.google.com/docs/cli?hl=ko)  
-Firebase Cloud Function (https://firebase.google.com/docs/functions?hl=ko)  

### MJU ECS
MJU ECS는 명지대학교 학생들을 위한 컨테이너 컴퓨팅 서비스입니다.  
AWS 의 ECS 와 유사한 기능을 가진 서비스 이며 명지대 학생들의 경우 무료로 사용할 수 있습니다
컨테이너를 생성하여 개발 환경을 자유롭게 구성하고 사용할 수 있습니다.  

### 컨테이너 규칙
- 컨테이너당 1개의 포트(out bound)를 설정할 수 있고 임의로 지정된 포트로 포트포워딩 되어 외부에서 접근 가능합니다.
- 1개의 컨테이너는 공평한 사용을 위해 2vcore, 3GB Memory 할당 고정 제공됩니다
- 3일 이상 사용하지 않은 컨테이너는 자동으로 정지 됩니다
- 3개월동안 로그인을 1번도 안 할시 모든 자원(컨테이너, 사용자 정보)가 삭제 및 회수 됩니다.

- 

### 보안
- 사용자의 정보는 학번을 제외하고 서버에 저장되지 않습니다
- 사용자의 학번 정보 또한 3개월 이상 사용하지 않을 시 자동으로 삭제됩니다 또한 언제든지 탈퇴가 가능하며 모든 사용자 정보는 탈퇴시 완전히 삭제 됩니다
- 로그인에 사용할 비밀번호와 컨테이너 터미널 접근시 사용할 비밀번호는 다릅니다 (학교 비밀번호로 사용하지 못합니다ㅠㅠ 저희는 사용자의 학교 비밀번호를 저장하지 않으며, 명지대 학생 인증에만 사용합니다), 비밀번호는 임의로 생성되며 해당 컨테이너 정보창에 비밀번호를 복사하는 버튼이 있습니다
-
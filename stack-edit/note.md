파일 서비스 정책

화면에서 업로드 하고 실제 저장까지
 
파일 업로드 
1. front-end에서 파일 올릴때 해당 파일을 임시 폴더에 임시 파일로 생성/저장
2. 임시 폴더에 파일을 생성하고 저장된 파일을 암호화 한후에  방금 생성한 파일에 암호화 된 내용을 쓴다.
3. back-end에서 파일을 저장할때 임시 폴더에 업로드 된 파일을 이동시킨다. 실제로 DB에도 업데이트를 할때 이 파일은 각 서비스 폴더 및 날짜 패턴에 맞춰진 폴더에 업로드 한다.

화면에서 첨부된 파일을 불러올때 까지
1. 백엔드에서 db에서 데이터를 로드하고 나서 파일id가 있다면 파일 서비스에 파일Id를 기반으로 파일을 조회하는 요청을 보낸다
2. 

<!--stackedit_data:
eyJoaXN0b3J5IjpbMTcwMDYwNTkzLC0xNDAzNDA2NzI4LC0xMz
gwMzkzNDY4LDQwODA4MDEzMSwtMjA4ODc0NjYxMiw5NDA5ODky
NDFdfQ==
-->
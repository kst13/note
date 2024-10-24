파일 서비스 정책

파일 업로드 
1. front-end에서 파일 올릴때 해당 파일을 임시 폴더에 임시 파일로 생성/저장
2. 임시 폴더에 파일을 생성하고 저장된 파일을 암호화 한후에  방금 생성한 파일에 암호화 된 내용을 쓴다.
3. back-end에서 파일을 저장할때 임시 폴더에 업로드 된 파일을 이동시킨다. 실제로 DB에도 업데이트를 할때 이 파일은 각 서비스 폴더 및 날짜 패턴에 맞춰진 폴더에 업로드 한다.
4. 
<!--stackedit_data:
eyJoaXN0b3J5IjpbNTEwNzgwNzIyLC0xMzgwMzkzNDY4LDQwOD
A4MDEzMSwtMjA4ODc0NjYxMiw5NDA5ODkyNDFdfQ==
-->
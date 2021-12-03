# OSS_vimgolf
_오픈소스SW개론 과제 vimgolf_solution_
***조선대학교 컴퓨터공학과 20203215 최윤영***


---------------

https://user-images.githubusercontent.com/68066598/144617877-d04628f5-1e8c-41f5-a388-89999caf73ec.mp4


<solution>
  첫 번째 풀이 ->
  <img src="https://user-images.githubusercontent.com/68066598/144618870-4e9e182f-967b-41ec-a7c9-c794c9c8608d.png" width="50%" height="50%"/>
  
  
    G : 파일의 마지막 줄로 이동
  
    A : 현재 라인의 끝에서 입력 모드 시작
  
    " 입력하기
  
    esc키 누르기 (일반모드로)
  
    /{ : 아래쪽으로 "{" 검색함 
  
    enter키 누르기
  
    i : 현재 위치에서 입력 모드 시작
  
    " 입력하기
  
    esc키 누르기 (일반모드로)
  
    ZZ누르기 (:wq : 저장하고 나가기 와 같은 기능)
  
  --> score 12


  두 번째 풀이 -> 동영상
    
    G : 파일의 마지막 줄로 이동
  
    W : 커서를 공백으로 구분된 다음 단어로 이동
  
    i : 현재 위치에서 입력 모드 시작
  
    end키 누르기(맨 뒤로)
  
    " 입력하기
  
    esc키 누르기 (일반모드로)
  
    ZZ누르기 (:wq : 저장하고 나가기 와 같은 기능)
  
  --> score 9

  
  -------------------------------------------
  

https://user-images.githubusercontent.com/68066598/144617881-d60c423b-24a3-4689-89ee-5644205f6c6c.mp4
  
<solution>
  첫 번째 풀이 ->
  <img src="https://user-images.githubusercontent.com/68066598/144623916-3281a630-fd33-471f-a329-945afe29ec79.png" width="50%" height="50%"/>
  
  
    :%s/sublime/vim/g : sublime → vim로 치환함
  
    :%s/emacs/vim/g : emacs → vim로 치환함

  
  --> score 36

  두 번째 풀이 -> 동영상
  
     :%s/sublime\|emacs/vim/g : sublime 과 emacs 를 vim 으로 치환함
  
  
----------------------------
  
  
https://user-images.githubusercontent.com/68066598/144617883-6d2d297b-12d0-4352-80dc-f8002733bfeb.mp4
  
 <solution>
  첫 번째 풀이 ->
  <img src="https://user-images.githubusercontent.com/68066598/144625706-20535099-8114-4ca1-b575-38a11bc73f46.png" width="50%" height="50%"/>
   
   
    M : 현재 화면 기준 중간으로 이동
  
    end키 누르기
  
    o : 현재 라인의 다음 줄에서 입력 모드 시작
  
    tab 누르기 
  
    // Version TODO 직접 타자 치기
  
    esc키 누르기 (일반모드로)
  
    j 눌러서 한 칸 아래로
  
    o : 현재 라인의 다음 줄에서 입력 모드 시작
  
    // Debug TODO 직접 타자 치기
   
    esc키 누르기 (일반모드로)
  
    ZZ누르기 (:wq : 저장하고 나가기 와 같은 기능)
  
  --> score 38
  
   
 <solution>
  두 번째 풀이 ->
  <img src="https://user-images.githubusercontent.com/68066598/144626966-71b5900a-f398-4498-8091-687fa02afbd6.png" width="50%" height="50%"/>

   
  
    :4 (네 번째 줄로 이동)
  
    enter키 누르기
  
    O : 현재 라인을 다음 줄로 밀고 입력 모드 시작
  
    tab 키 누르기
  
    // Version TODO 직접 타자 치기
  
    esc키 누르기 (일반모드로)
  
    :6 (여섯 번째 줄로 이동)
   
    O : 현재 라인을 다음 줄로 밀고 입력 모드 시작
   
    // Debug TODO 직접 타자 치기
   
    esc키 누르기 (일반모드로)
  
    ZZ누르기 (:wq : 저장하고 나가기 와 같은 기능)
  
  --> score 40

                                                                                                                                          
                                                                                                                                          
https://user-images.githubusercontent.com/68066598/144617885-caf39a37-7211-41d6-ace8-3b5f509b7639.mp4


https://user-images.githubusercontent.com/68066598/144617868-1215ddb9-735e-4c40-a2ca-49a5afcc665e.mp4

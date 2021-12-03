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
  
  --> score 27
  
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


 <solution>
  세 번째 풀이 -> 동영상
   
   
    5 Shift _ : 5번째 줄로 이동 (:5 랑 같다)
  
    qq : qq는 이 후 입력을 q 레지스터에 기록
  
    P : 현재 위치에 붙여넣기
  
    i : 현재 위치에서 입력 모드 시작
  
    // 직접 타자 치기
  
    esc키 누르기 (일반모드로)
  
    2w : w를 두 번하는 거랑 같은 기능
   
    C : 현재 위치부터 라인 끝까지 삭제 후 입력 모드 시작
   
    TODO 직접 타자 치기
   
    esc키 누르기 (일반모드로)
   
    q : 매크로 기록
   
    k : 바로 위로
   
    @ + q : 매크로 실행 (// Version TODO 가 바로 쳐짐)
  
    ZZ누르기 (:wq : 저장하고 나가기 와 같은 기능)
  
  --> score 25
   
   
--------------------------------------
   
                                                                                                                                          
https://user-images.githubusercontent.com/68066598/144617885-caf39a37-7211-41d6-ace8-3b5f509b7639.mp4
   
   
 <solution>
  첫 번째 풀이 ->
   
   <img src="https://user-images.githubusercontent.com/68066598/144634432-b4dc3999-8377-4a92-b461-b0252d2f6365.png" width="70%" height="70%"/>
   
   
    :2,2s/y1/abs(y1)/g (두 번째 줄에 있는 y1를 abs(y1) 로 치환하겠다)
  
    :3,3s/y1/abs(y2)/g (세 번째 줄에 있는 y1를 abs(y2) 로 치환하겠다)
  
    :4,4s/y1/abs(y3)/g (네 번째 줄에 있는 y1를 abs(y3) 로 치환하겠다)
  
    :5,5s/y1/abs(y4)/g (다섯 번째 줄에 있는 y1를 abs(y4) 로 치환하겠다)
  
    :3s/1/2/g (세 번째 줄에 있는 1를 2로 치환하겠다)
  
    :4s/1/3/g (네 번째 줄에 있는 1를 3로 치환하겠다)
   
    :5s/1/4/g (다섯 번째 줄에 있는 1를 4로 치환하겠다)
   
    :3s/k/b/g (세 번째 줄에 있는 k를 b로 치환하겠다)
   
    :4s/k/r/g (네 번째 줄에 있는 k를 r로 치환하겠다)
   
    :5s/k/g/g (다섯 번째 줄에 있는 k를 g로 치환하겠다)
  
    ZZ누르기 (:wq : 저장하고 나가기 와 같은 기능)
  
  --> score 139

   
 <solution>
  두 번째 풀이 -> 동영상
   
   
    :%s/y1/abs(y1)/g (모든 문자열y1을 abs(y1)로 치환하겠다)
  
    :3s/1/2/g (세 번째 줄에 있는 1를 2로 치환하겠다)
   
    :3s/k/b/g (세 번째 줄에 있는 k를 b로 치환하겠다)
  
    :4s/1/3/g (네 번째 줄에 있는 1를 3로 치환하겠다)
   
    :4s/k/r/g (네 번째 줄에 있는 k를 r로 치환하겠다)
   
    :5s/1/4/g (다섯 번째 줄에 있는 1를 4로 치환하겠다)
   
    :5s/k/g/g (다섯 번째 줄에 있는 k를 g로 치환하겠다)
  
    ZZ누르기 (:wq : 저장하고 나가기 와 같은 기능)


  --> score 79
   
   
   
--------------------------------------------
   
https://user-images.githubusercontent.com/68066598/144617868-1215ddb9-735e-4c40-a2ca-49a5afcc665e.mp4
   
   
 <solution>
  첫 번째 풀이 ->
   <img src="https://user-images.githubusercontent.com/68066598/144636668-ecdefe2d-6675-4fce-862a-a77f35289834.png" width="70%" height="70%"/>

   
    :5 (다섯 번째 줄로 이동)
  
    enter키 누르기
   
    yw : 현재 word의 끝까지 복사함
  
    :10 (열 번째 줄로 이동)
   
    enter키 누르기
   
    end키 누르기
   
    P(대문자) : 현재 위치에 붙여넣기
   
    a : 현재 위치 다음 칸에서 입력 모드 시작
   
    , (콤마) 직접 입력
   
    esc키 누르기
   
    M키 누르기 (화면 기준 가운데로 이동)
   
    yw : 현재 word의 끝까지 복사함
   
    :10 (열 번째 줄로 이동)
   
    enter키 누르기
   
    end키 누르기
   
    P(대문자) : 현재 위치에 붙여넣기
   
    a : 현재 위치 다음 칸에서 입력 모드 시작
   
    , (콤마) 직접 입력
   
    esc키 누르기
   
    ... ( 7번째 줄과 8번째 줄도 똑같이 반복)
  
    ZZ누르기 (:wq : 저장하고 나가기 와 같은 기능)

   
   
 <solution>
  두 번째 풀이 -> 동영상
   
    :5 (다섯 번째 줄로 이동)
  
    enter키 누르기
   
    yw : 현재 word의 끝까지 복사함
  
    :10 (열 번째 줄로 이동)
   
    enter키 누르기
   
    end키 누르기
   
    P(대문자) : 현재 위치에 붙여넣기
   
    a : 현재 위치 다음 칸에서 입력 모드 시작
   
    ,,, (콤마 세 개) 직접 입력
   
    esc키 누르기
   
    M키 누르기 (화면 기준 가운데로 이동)
   
    yw : 현재 word의 끝까지 복사함
   
    :10 (열 번째 줄로 이동)
   
    enter키 누르기
   
    end키 누르기
   
    h 두 번 누르기 (왼 쪽으로 두 번 이동)
   
    P(대문자) : 현재 위치에 붙여넣기
   
    ... ( 7번째 줄과 8번째 줄도 똑같이 반복)
  
    ZZ누르기 (:wq : 저장하고 나가기 와 같은 기능)

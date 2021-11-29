# VimGolf_5-


## 1번 (vimgolf put 5f0f5fbe280fbf000c233304)

* 최고점 : 8

* 내가 나온 점수 : 9

![ezgif com-gif-maker](https://user-images.githubusercontent.com/86939460/143795552-6680e11a-060d-4d94-a83e-10781cdcd459.gif)

  __* 해결 경로__

  GWi"<kEnd>"<Esc>ZZ
  
  __* 설명__
  
 1) G - 마지막 줄로 이동
 2) w - 단어 단위 앞으로 이동(단어 시작)해서 {로 이동
 3) i -  현재 위치에서 입력 모드 시작해서 " 입력
 4) End - 라인 끝으로 이동후 "입력
 5) ZZ - 빠져나오기
  
## 2번 (vimgolf put 603ba26a01b4d00009c10a49)
  
• 최고점 : 19
  
• 내가 나온 점수 : 27
  
![ezgif com-gif-maker (1)](https://user-images.githubusercontent.com/86939460/143795566-fdff0538-bb3d-459b-a98c-08f69fc1e490.gif)
  
 __* 해결 경로__
  
 :%s/sublime\|emacs/vim/g<CR>ZZ
  
  __* 설명__
  
 1) :%s/sublime\|emacs/vim/g - sublim or emacs를 vim으로 바꾼다. 
  
    
## 3번 (vimgolf put 5f1063aa8361810006e73210)

• 최고점 : 20
  
• 내가 나온 점수 : 36
  
![ezgif com-gif-maker (2)](https://user-images.githubusercontent.com/86939460/143795571-0b231553-fcf1-4080-a90b-ec42d7571d03.gif)

   __* 해결 경로__
  
  :4<CR>ywO// <Esc>paTODO<Esc>:6<CR>ywO// <Esc>paTODO<Esc>ZZ
  
  __* 설명__
  
 1) :4 - 4번 라인으로 이동
 2) yw - Version 복사
 3) O - 현재 라인을 다음 줄로 밀고 입력 모드 시작
 4) // (스페이스로 한칸 띄운뒤) Esc p - : p를 사용하여 현재위치 다음에 붙여넣기
 5) :6 - 6번 라인으로 이동
 6) 위에서 했던 것 과 동일하게 yw로 Debug를 복사하고 O로 입력모드에 들어간 후 p를 사용해서 복사붙여넣기를 한 후 마지막으로 TODO작성

## 4번 (vimgolf put 9v0060da5177000000000209)
  
• 최고점 : 19
  
• 내가 나온 점수 : 69
  
![ezgif com-gif-maker (3)](https://user-images.githubusercontent.com/86939460/143795580-a5950b00-bbf9-461b-9e49-b5ec02f4b73b.gif)

![ezgif com-gif-maker (4)](https://user-images.githubusercontent.com/86939460/143795583-862f1c3a-cbaa-41ab-8259-34fcf07a2284.gif)

  __* 해결 경로__
  
<Down>f1a<Down><BS>2<Down><BS>3<Down><BS>4<Esc><Down>f1a<Down><BS>2<Down><BS>3<Down><BS>4<Esc>:%s/y1/abs(y)<CR>fya4<Up><Left>3<Up><Left>2<Up><Left>1<Esc>fka<Down><BS>b<Down><BS>r<Down><BS>g<Esc>f1a<BS>4<Up><BS>3<Up><BS>2<Esc>ZZ<CR>fya4<Up><Left>3<Up><Left>2<Up><Left>1<Esc>fka<Down><BS>b<Down><BS>r<Down><BS>g<Esc>f1a<BS>4<Up><BS>3<Up><BS>2<Esc>ZZ
 
  __* 설명__
  
  1) f 1 - 숫자 1이 있는 곳으로 이동.
  2) 내려가며 숫자1을 2, 3, 4으로을 수정.
  3) :%s/y1/abs(y) - y1을 abs(y)로 치환    #비주얼 블록 모드를 사용 하고 싶었지만 ctrl+v, ctrl+q를 사용해도 사용이 안 되었습니다.. 
  4) 후에 fy로 ㅛ를 찾아 이동 하고 a로 현재 위치 다음 칸에서 입력 모드를 시작하여 y1, y2, y3, y4 로 수정.
  5) fk로 k로 이동 a를 눌러 k를 b, r, g로 수정 후 f1로 1를 찾아 이동 후 a로 다시 숫자 수정.
  6) esc, ZZ - 일반모드로 변환후 빠져나오기
  
## 5번 (vimgolf put 6013804df3308e0009368f1c)

  • 최고점 : 19

  • 내가 나온 점수 : 31

![ezgif com-gif-maker (6)](https://user-images.githubusercontent.com/86939460/143796277-71a5e120-994e-4707-b2a3-ec623f7a7edc.gif)

   __* 해결 경로__
  
  :5<CR>yw:10<CR>f"pa,name,age,score<Esc>ZZ
  
  __* 설명__
  
 1) :5 - 5번 라인으로 이동
 2) yw - 현재 word를 끝까지 복사하여 student_id를 복사.
 3)  :10 - 10번 라인으로 이동
 4) f " - f 명령어를 사용하여 현재 라인에 "가 있는지 검색해서 그 부분으로 이동
 5) p - 현재위치 다음에 붙여넣기
 6) name,age,score를 적어줌 (이렇게 그냥 적어주는 게 명령어 써서 하는 것보다 점수가 더 낮게 나오더라구요..)
 7) esc, ZZ - 일반모드로 변환후 빠져나오기
  
.

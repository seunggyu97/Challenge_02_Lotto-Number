# Challenge_02
## 로또 번호 추첨기

최대 5개 까지 NumberPicker를 이용하여 사용자로부터 번호를 입력받고

나머지 숫자들은 랜덤하게 선택하여 6개의 숫자를 만든다.

선택된 숫자들은 중복으로 다시 선택될 수 없고, 랜덤으로 뽑는 수에서 제외한다.

Shape Drawable을 사용하여 1부터 10까지는 노란색, 11부터 20까지는 파란색, 21부터 30까지는 빨간색, 31부터 40까지는 회색, 이외에는 초록색으로 공모양의 형태를 보여준다.

만약 중복된 숫자들이 선택되거나 번호를 랜덤 생성한뒤 번호를 추가하려는 경우 예외처리를 적용한다.

## 학습 내용
* Layout
** ConstraintLayout
** NumberPicker
** TextView(복습)
** Button(복습)
* 중복 코드 정리
* Shape Drawable 사용

* Kotlin 문법
** apply
** when
** random
** Collection
*** Set, List
** 람다 함수

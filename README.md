# Code Highlighter

© 2018 Dark Tornado, All rights reserved.

You can highlight your source code in EditText.<br>
It support only reserved words in Javascript, but you can add reserved word by using .addReservedWord(); method, remove reserved word by using .removeReservedWord(); method.<br>


EditText에 있는 소스코드를 하이라이팅할 수 있습니다.<br>
예약어들은 자바스크립트에 있는 예약어들만 지원하며, addReservedWord(); 메소드로 하이라이팅될 예약어를 추가하거나, .removeReservedWord(); 메소드로 삭제하는 것이 가능합니다.<br>

## How to Use (사용법)

1. Download .jar file.<br>
  .jar 파일을 다운로드 받습니다.

[Download(다운로드)](https://github.com/DarkTornado/CodeHighlighter/raw/master/release/CodeHighlighter-v.1.0.jar)

2. Add .jar file to libs folder in your project.<br>
  .jar 파일을 프로젝트 폴더 안에 있는 libs 폴더에 넣습니다.<br><br>
<img src="https://raw.githubusercontent.com/DarkTornado/CodeHighlighter/master/CodeHighlighterImage1.jpg"><br><br>
<img src="https://raw.githubusercontent.com/DarkTornado/CodeHighlighter/master/CodeHighlighterImage2.jpg"><br><br>
<img src="https://raw.githubusercontent.com/DarkTornado/CodeHighlighter/master/CodeHighlighterImage3.jpg"><br><br>
<br>

3. Right-Click .jar file and click "Add As Linbrary...".<br>
  .jar 파일을 우클릭해서 Add As Linbrary... 클릭.<br>
<img src="https://raw.githubusercontent.com/DarkTornado/CodeHighlighter/master/CodeHighlighterImage4.jpg"><br><br>

4. Click "OK" burron.<br>
  "OK" 버튼 클릭<br>
<img src="https://raw.githubusercontent.com/DarkTornado/CodeHighlighter/master/CodeHighlighterImage5.jpg"><br><br>

5. Then, it will be added to gradle, too.<br>
  그러면 이렇게 알아서 gradle에도 추가됩니다.<br>
<img src="https://raw.githubusercontent.com/DarkTornado/CodeHighlighter/master/CodeHighlighterImage6.jpg"><br><br>



## API

- <b>new CodeHighlighter();</b><br>
Create CodeHighlighter instance.<br>
CodeHighlighter 인스턴스 생성
<br>

- <b>.addReservedWord(String word);</b><br>
Add reserved word to highlight.<br>
하이라이팅할 예약어 추가.

- <b>.addReservedWord(String word, int color);</b><br>
Add reserved word to highlight. Can choose highlight color.<br>
하이라이팅할 예약어 추가. 하이라이팅 색상도 선택 가능.

- <b>.removeReservedWord(String word);</b><br>
Remove reserved word from list which will be highlight(?).<br>
하이라이팅될 예약어 목록에서 해당 예약어 삭제.

- <b>.clearReservedWord();</b><br>
Clear reserved words to highlight.<br>
하이라이팅할 모든 예약어 삭제.

- <b>.setReservedWordHighlightColor(int color);</b><br>
Set highlight color that will be applied to reserved word. It will not be applied to reserved word that was added by using .addReservedWord(String word, int color);<br>
예약어 하이라이팅에 사용될 색상 설정. .addReservedWord(String word, int color);로 추가한 예약어에는 적용되지 않음.

- <b>.setReservedWordHighlightColor(int color);</b><br>
Set highlight color that will be applied to reserved word.<br>
예약어 하이라이팅에 사용될 색상 설정.

- <b>.setNumberHighlightColor(int color);</b><br>
Set highlight color that will be applied to number.<br>
숫자 하이라이팅에 사용될 색상 설정.

- <b>.setStringHighlightColor(int color);</b><br>
Set highlight color that will be applied to string.<br>
문자열 하이라이팅에 사용될 색상 설정.

- <b>.setAnnotationHighlightColor(int color);</b><br>
Set highlight color that will be applied to annotation.<br>
주석 하이라이팅에 사용될 색상 설정.

- <b>.apply(Editable s);</b><br>
Apply Highlighting<br>
하이라이팅 적용



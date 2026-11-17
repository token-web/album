자체 호스팅 글꼴 안내 (나의 추억 앨범 만들기)
==========================================

이 폴더의 글꼴 파일은 구글 폰트(https://fonts.google.com)에서 제공하는 오픈 글꼴을
웹용(woff2)으로 가공한 것입니다. 모두 SIL Open Font License 1.1 (OFL) 로 배포되며,
웹사이트와 그 결과물(PDF·PNG)에 사용하는 것은 무료입니다. 라이선스 전문은 같은 폴더의 OFL-*.txt 입니다.

[ 글꼴 ]
- Noto Sans KR   : Copyright 2014-2021 Adobe (http://www.adobe.com/), with Reserved Font Name 'Source'
                   -> OFL-notosanskr.txt            (고딕)
- 나눔명조        : Copyright (c) 2010, NHN Corporation (http://www.nhncorp.com)
                   -> OFL-nanummyeongjo.txt         (명조)
                   ※ 이 글꼴은 '예약 글꼴 이름'이 지정되어 있어, 가공한 파일의 내부 이름을
                     "Myeongjo KR Web" 으로 바꾸었습니다. (파일명: myeongjo-kr-*)
- Gaegu          : Copyright 2018 The Gaegu Project Authors
                   -> OFL-gaegu.txt                 (손글씨)

[ 가공 내용 ]
- 글꼴 원본: https://github.com/google/fonts (ofl/notosanskr, ofl/nanummyeongjo, ofl/gaegu)
- 필요한 글자만 추려 woff2 로 변환했습니다. (Noto Sans KR 는 굵기 400/700 의 개별 글꼴로 만듦)
- *-core.woff2 : 영문·숫자·기호와 자주 쓰는 한글 2,350자 (평소에 이것만 내려받음)
- *-ext.woff2  : 나머지 한글 음절 (입력한 글자에 필요할 때만 자동으로 내려받음)
- gaegu-*.woff2 : 개구 글꼴 (원래 한글 2,350자를 지원)
- fonts.css    : 위 파일을 연결하는 @font-face 설정

글꼴 파일은 직접 수정하지 마세요.

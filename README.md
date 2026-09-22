# example-github-ci-cd



# 연산자

| 종류 | 연산자 |
|---|---|
| 논리연산 | ! , && , \|\|              |
| 비교연산 | ==,  != , >= , <= , >, < |
| 그루핑 | ( ) |
| 인덱스 | [ ] |
| 속성참조 | . |


# 객체 필터
>> ${{ github.event.*.html_url }} # 별표(\*)로 객체 필터 정의

- 깃허브 콘텍스트의 event 객체로부터 html_url 속성만 추출해서 배열을 생성.
- 객체 필터는 함수와 함께 자주 사용.


# 함수
|종류|함수|
|---|---|
|문자열 비교| contains( ), startsWith( ), endsWith( ) |
|문자열 생성| format( ), join( ) |
|JSON처리| toJSON( ), fromJSON( ) |
|해시 생성| hashFiles( ) |

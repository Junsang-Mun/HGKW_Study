# 챕터 2



## 정보의 단위

### Bit

- 가장 작은 정보의 단위
- 0 혹은 1로 나타낼 수 있음

| 1byte | 8bit                  |
| ----- | --------------------- |
| 1kB   | 1000byte (1024 bytes) |
| 1MB   | 1000kB (1024 kBs)     |
| 1GB   | 1000MB (1024 MBs)     |
| 1TB   | 1000GB (1024 GBs)     |

### 진법

#### Binary: 이진법

![Binary는 호남선~](https://d2u3dcdbebyaiu.cloudfront.net/uploads/atch_img/298/bb849c6cab722ec056173453e89aa315_res.jpeg)

**표현** : 1000(2) / **0b**1000

**음수** : a라는 숫자에 대해 음수를 만들 때 → (2<sup>n</sup> - a)을 이진법으로 / 혹은 각 자리수의 0과 1을 flip하고 1 더하기

**플래그** : 음수인지 양수인지 몰?루? → Flag값을 가지고 있어서 컴퓨터는 알고계신대 누가 음수인지 양수인지~ 오늘밤에 다녀가신대~



#### Hexadecimal: 십육진법

**표현** : 3A(16) / **0x**3A

**진법** : 0123456789ABCDEF

**이진법으로** : 4자리씩 끊어서 16진법 변환



## 0과 1로 문자를 표현하는 방법

### Character Set

컴퓨터가 이해할 수 있는 문자의 집합, Character set에 없는 문자는 컴퓨터에서 이해하지 못함

대표적인 character set:

- ASCII Code
- Unicode
- EUC-KR
- KS X 시리즈

#### Character encoding

문자를 기계어로 번역하는 과정.

하나의 문자에 대해서 다양한 인코딩이 있을 수 있음 (예시. A @ascii → 65, @unicode → U+0041)

유니코드 인코딩 방식인 [UTF](https://en.wikipedia.org/wiki/Unicode#UTF)도 참고해보시길

#### Character decoding

기계어를 문자로 번역하는 과정.

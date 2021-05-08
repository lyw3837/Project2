# Basic Syntax

## Heading
제목을 만들기 위해서는 단어 혹은 문장 앞에 #표시를 사용하여 나타냅니다. 단어나 문장 앞에 붙이는 #표시의 수는 제목의 level을 나타내며 level이 높을수록 제목의 크기는 작아집니다.  

**주의)** 또한 #표시와 단어나 문장 사이에는 빈공간이 필요합니다.

## Paragraph
단락을 나누기 위해서는 단락과 단락 사이의 한 줄을 비우면서 단락을 나눌 수 있습니다.

## Line Breaks
줄을 바꾸기 위해서는 문장 마지막에 두개 혹은 그 이상의 빈공간을 넣음으로써 문장의 줄을 바꿀 수 있습니다.

## Emphasis
- **Bold** - 글자를 두껍게 만들어서 강조하기 위해서는 단어나 문장 사이의 **표시를 빈공간없이 붙여씀으로써 글자를 강조할 수 있습니다.  
  ex) I \*\*love\*\* chicken -> I **love** chicken

- **Italic** - 글자를 기울어지게 만들어서 강조하기 위해서는 단어나 문장 사이의 *표시를 빈공간없이 붙여씀으로써 글자를 강조할 수 있습니다.  
ex) I \*love\* chicken -> I *love* chicken

- **Bold and Italic** -글자를 두껍고 기울어지게 만들어서 강조하기 위해서는 단어나 문장 사이의 ***표시를 빈공간없이 붙여씀으로써 글자를 강조할 수 있습니다.  
ex) I \*\*\*love\*\*\* chicken -> I ***love*** chicken

## Blockquotes
- Blcokquotes를 사용하기 위해서는 단락 앞에 >을 사용합니다.  
**ex)**  
\> I love chicken  
**output** 
    > I love chicken

- Blockquotes는 여러 단락에서도 사용할 수 있습니다.  
또한 단락 사이 빈 줄에 >표시를 사용해야 합니다.  
**ex)**  
    \> I love chicken  
    \>  
    \> I love pizza  
    **output** 
    > I love chicken
    >
    > I love pizza 

- Blockquotes 안에 Blockquotes를 사용할 수 있습니다.  
**ex)**  
\> I love chicken  
\>> I love pizza  
**output** 
    > I love chicken
    >  
    >> I love pizza
## Lists
- 정렬된 리스트를 만들기 위해서는 숫자와 마침표를 맨 앞에 사용합니다.
  마침표 앞에 쓰는 숫자는 순서와 상관이 없지만 목록은 숫자 1로 시작해야합니다. 
- 정렬되지 않은 리스트를 만들기 위해서는 -, +, * 을 맨 앞에 사용합니다.  
- 리스트에 들여쓰기를 통해서 단락, Blockquotes, 코드블록, 이미지, 목록을 추가 할 수 있씁니다.
## Code
- 단어나 문장을 코드로 나타내려면 '표시를 단어나 문장 처음과 끝에 사용합니다.
- Escaping Backticks - 코드로 나타내려는 문장에 '표시가 하나 이상 포함되 있는 경우 단어나 문장 처음과 끝에 '을 두번 사용합니다.  
- Code blocks - 코드블록을 만들려면 모든 줄의 빈공간이 4개 이상이거나 텝으로 들여쓰기를 해야합니다. 

## Horizontal Rules
줄을 사용하기 위해서는 ***, ---, ___을 사용하고 그 전후로 빈줄을  사용하면 줄이 그어집니다.  
**ex)**  
I love chicken   

\---

I love pizza  

**output**  

I love chicken

---

I love pizza

## Links
- 링크를 달기 위해서는 링크를 달 글자에 [] 기호를 사용하고 바로 뒤에 ()표시와 그 안에 URL를 넣으면 됩니다.  
**ex)**  
I love \[chicken](https://www.bbq.co.kr/).  
**output**  
I love [chicken](https://www.bbq.co.kr/).  

- Adding Titles - 링크에 마우스 포인트를 갖다대면 설명이 나오게 하려면 URL 이후 괄호("")안에 설명을 쓰면 됩니다.  
**ex)**  
I love \[chicken](https://www.bbq.co.kr/ "BBQ치킨").  
**output**  
I love [chicken](https://www.bbq.co.kr/ "BBQ치킨").  

- URLs and Email Addresses - URL이나 이메일을 빠르게 킬수 있도록 하려면 <>표시를 사용하면 됩니다.  

## Images
- 이미지를 추가하기 위해서는 !와[]표시와 괄호안에는 alt text를 쓴 후 ()표시와 괄호안에는 이미지 주소나 URL을 쓴다. URL 옆에 선택적으로 설명을 추가할 수 있습니다.  
**ex)**  
\!\[chicken](/assets/images/bbq.png "chicken")  
**output**  
  
    ![chicken](/assets/images/bbq.png "chicken")

- Linking Images -이미지와 링크를 연결시키기 위해서는 이미지의 Markdown을 []로 둘러싼 후 옆에 ()을 열어 링크를 추가합니다.  
**ex)**  
\[\!\[chicken](/assets/images/bbq.png "chicken")](https://www.bbq.co.kr/)  
**output**  
    [![chicken](/assets/images/bbq.png "chicken")](https://www.bbq.co.kr/)
## Escaping Charaters
다음 기호들은 \와 함께 사용하면 출력할 때 기능을 하지 않고 그대로 출력됩니다.  
\\  
\'  
\*  
\_  
\{}  
\[]  
\<>  
\()  
\#  
\+  
\-  
\.  
\!  
\|


github.com/lyw3837
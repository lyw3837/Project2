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
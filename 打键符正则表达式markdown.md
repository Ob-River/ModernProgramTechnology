
��Ȼ����  
```java
��Ȼ����  
��Ȼ����
```
```java
��Ȼ����

��Ȼ����
```
#h1
##h2#
######h6######
��������˳λ�̳У�ÿ��4���ո��1���Ʊ��
>����
>>�����е����á�
�б�����˳λ�̳У�ÿ��4���ո��1���Ʊ����
- Red
- Green
- Blue
1.Bird
2.McHale
3.Parish
���׳�������-Ӣ����-�հף�Ҫ����������״�����ھ��ǰ����Ϸ�б�ܣ�
1986\. What a great year.
�ָ��ߣ���Ҫ�б���ַ���
* * *
***
*****
- - -
----------
___
ǿ�������Ҳ����пո�
**ǿ��**
__ǿ��__
~~ɾ����~~
*��б*
_��б_
linein code `linein code`.
```java
linein code `linein code`.
```
![runoob logo](http://static.runoob.com/images/runoob-logo.png)
![�ҵ���Ƭ](images/�ҵ���Ƭ.jpg)
��[logo][id001]��Ϊ������ַ������Ȼ�����ĵ���βΪ������ֵ���ӡ�
[logo]:http://static.runoob.com/images/runoob-logo.png
```java
![runoob logo](http://static.runoob.com/images/runoob-logo.png)
![�ҵ���Ƭ](images/�ҵ���Ƭ.jpg)
��[logo][id001]��Ϊ������ַ������Ȼ�����ĵ���βΪ������ֵ���ӡ�
[id001]:http://static.runoob.com/images/runoob-logo.png
```
|  ��ͷ   | ��ͷ  |
|  ----  | ----  |
| ��Ԫ��  | ��Ԫ�� |
| ��Ԫ��  | ��Ԫ�� |

| ����� | �Ҷ��� | ���ж��� |
| :-----| ----: | :----: |
| ��Ԫ�� | ��Ԫ�� | ��Ԫ�� |
```java
|  ��ͷ   | ��ͷ  |
|  ----  | ----  |
| ��Ԫ��  | ��Ԫ�� |
| ��Ԫ��  | ��Ԫ�� |

| ����� | �Ҷ��� | ���ж��� |
| :-----| ----: | :----: |
| ��Ԫ�� | ��Ԫ�� | ��Ԫ�� |
```
<u>���»����ı�</u>
�۵�ע��

```
:joy:
```java
:joy:
```

���� Markdown ��Χ�ģ�����HTML5��CSS3��֮�ڵı�ǩ��������ֱ��׫д��Ŀǰ֧���У�<kbd> <b> <i> <em> <sup> <sub> <br>
ʹ�� <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>Del</kbd> �������ԡ�
```java
ʹ�� <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>Del</kbd> �������ԡ�
```
��ѧ��ʽ
$$
\mathbf{V}_1 \times \mathbf{V}_2 =  \begin{vmatrix} 
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
\frac{\partial X}{\partial u} &  \frac{\partial Y}{\partial u} & 0 \\
\frac{\partial X}{\partial v} &  \frac{\partial Y}{\partial v} & 0 \\
\end{vmatrix}
${$tep1}{\style{visibility:hidden}{(x+1)(x+1)}}
$$
```math
$$
\mathbf{V}_1 \times \mathbf{V}_2 =  \begin{vmatrix} 
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
\frac{\partial X}{\partial u} &  \frac{\partial Y}{\partial u} & 0 \\
\frac{\partial X}{\partial v} &  \frac{\partial Y}{\partial v} & 0 \\
\end{vmatrix}
${$tep1}{\style{visibility:hidden}{(x+1)(x+1)}}
$$
```
1. ��������ͼԴ���ʽ��
```mermaid
graph LR
A[����] -->B(Բ��)
    B --> C{����a}
    C -->|a=1| D[���1]
    C -->|a=2| E[���2]
    F[��������ͼ]
```
2. ��������ͼԴ���ʽ��
```mermaid
graph TD
A[����] --> B(Բ��)
    B --> C{����a}
    C --> |a=1| D[���1]
    C --> |a=2| E[���2]
    F[��������ͼ]
```
3. ��׼����ͼԴ���ʽ��
```flow
st=>start: ��ʼ��
op=>operation: �����
cond=>condition: �жϿ�(�ǻ��?)
sub1=>subroutine: ������
io=>inputoutput: ���������
e=>end: ������
st->op->cond
cond(yes)->io->e
cond(no)->sub1(right)->op
```
4. ��׼����ͼԴ���ʽ�����򣩣�
```flow
st=>start: ��ʼ��
op=>operation: �����
cond=>condition: �жϿ�(�ǻ��?)
sub1=>subroutine: ������
io=>inputoutput: ���������
e=>end: ������
st(right)->op(right)->cond
cond(yes)->io(bottom)->e
cond(no)->sub1(right)->op
```
5. UMLʱ��ͼԴ��������
```sequence
����A->����B: ����B�����?������
Note right of ����B: ����B������
Note left of ����A: ����A������(��ʾ)
����B-->����A: �Һܺ�(��Ӧ)
����A->����B: ����ĺ���
```
6. UMLʱ��ͼԴ�븴��������
```sequence
Title: ���⣺����ʹ��
����A->����B: ����B�����?������
Note right of ����B: ����B������
Note left of ����A: ����A������(��ʾ)
����B-->����A: �Һܺ�(��Ӧ)
����B->С��: �����
С��-->>����A: ����B������
����A->����B: ����ĺ���
Note over С��,����B: ����������
participant C
Note right of C: û��������
```
7. UML��׼ʱ��ͼ������
```mermaid
%% ʱ��ͼ����,-> ֱ�ߣ�-->���ߣ�->>ʵ�߼�ͷ
  sequenceDiagram
    participant ����
    participant ����
    ����->����: ���������
    loop �������
        ����->����: �뼲��ս��
    end
    Note right of ����: ���� ʳ�� <br/>��ҽ��...
    ����-->>����: �ܺ�!
    ����->����: ����ô��?
    ����-->����: �ܺ�!
```
8. ����ͼ������
```mermaid
%% �﷨ʾ��
        gantt
        dateFormat  YYYY-MM-DD
        title �����������ͼ
        section ���
        ����                      :done,    des1, 2014-01-06,2014-01-08
        ԭ��                      :active,  des2, 2014-01-09, 3d
        UI���                     :         des3, after des2, 5d
    δ������                     :         des4, after des3, 5d
        section ����
        ѧϰ׼���������                      :crit, done, 2014-01-06,24h
        ��ƿ��                             :crit, done, after des2, 2d
        ����                                 :crit, active, 3d
        δ������                              :crit, 5d
        ˣ                                   :2d
        section ����
        ���ܲ���                              :active, a1, after des3, 3d
        ѹ������                               :after a1  , 20h
        ���Ա���                               : 48h
```
***
windows��Դ������
? ƥ�� 0 ���� 1 ���ַ���* ƥ��0�������ַ���
***
^ Ϊƥ�俪ʼλ�á�
[0-9]+ƥ�������֣�[]��Ϊ���壬�޶���-���Ӵ�0��9��[0-9] ƥ��һ�����֣�+ ƥ��һ�����߶����
abc$ƥ����ĸ abc ���� abc ��β��$ Ϊƥ�����λ�á�
^[0-9]+abc$
^[a-z0-9_-]{3,15}$  {3,15}$�����޶��ַ�����>=3��<=15��a-z��0-9��_��-������ƥ�� `runoob``runoob1``run-oob``run_oob`�� ����ƥ�� `ru`����Ϊȱ����С�� `3` ���޷�ƥ�䡣Ҳ��ƥ�� `runoob$`�� ��Ϊ���������ַ���

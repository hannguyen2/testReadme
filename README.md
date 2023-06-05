# Markdown syntax guide
# Guideline A/B Testing

## Headers
## Mục đích sử dụng

# This is a Heading h1
## This is a Heading h2 
###### This is a Heading h6
Override một bộ config cùng đặc tính (cùng field, cùng value) trên một feature cho một tập User cố định, được chọn sẵn trong ABgroup hoặc được chia ngẫu nhiên, theo tỉ lệ và tự động bằng Janus.

## Emphasis

*This text will be italic*  
_This will also be italic_

**This text will be bold**  
__This will also be bold__

_You **can** combine them_

## Lists

### Tạo Namespace trên Janus 
#### Bước 1: 

* Nhấn vào link janus [Janus MT DEV](https://janus-dev.mservice.io/report/).
* Nhấn vào link Janus [Janus MT PROD](https://janus.mservice.io/report/).
* Nếu đã được tạo sẵn namespace thì cần xin owner để add quyền vào namesapce đó 

#### Bước 2: Bấm vào nút [Namespace] ở mục A/B Testing
#### Bước 3: Bấm vào create
#### Bước 4: Nhập đầy đủ các fields bắt buộc (lưu ý: Phải bật ON field [Use For Web Admin])

<img src="https://img.mservice.com.vn/app/media/Webadmin/ab_testing/b4janus.png" alt="Feature_pic1" width=5000></img><br/>
#### Bước 5: Nhấn nút [Create Namespace] => Nhấn nút [Okay]
### Tạo Experiment trên Janus
#### Bước 1: Khi tạo Namespace thành công. Ở mục Manage Experiments nhấn vào nút [New Experiment]
#### Bước 2: Nhập các fields bắt buộc 
#### Bước 3: Nhấn nút [Next]
#### Bước 4: Ở mục "Variations" có thể add /edit /remove
#### Bước 5: Nhấn nút [Next]
#### Bước 6: Nhấn nút [Next]
#### Bước 7: Ở mục "New Experiment" chọn "Product" và "Project"
#### Bước 8: Nhấn nút [Finish]
#### Bước 9: Nhấn nút [Okay]
### Xem trạng thái rollout trên Janus 
Sẽ có 3 trạng thái: 
* DRAFT
* RUNNING 
* OFF

__Ba trạng thái này sẽ không được start trực tiếp trên Janus mà nó sẽ phụ thuộc vào Webadmin__




### Ordered

1. Item 1
1. Item 2
1. Item 3
  1. Item 3a
  1. Item 3b

## Images

![This is a alt text.](/image/sample.png "This is a sample image.")

## Links

You may be using [Markdown Live Preview](https://markdownlivepreview.com/).

## Blockquotes

> Markdown is a lightweight markup language with plain-text-formatting syntax, created in 2004 by John Gruber with Aaron Swartz. 
>
>> Markdown is often used to format readme files, for writing messages in online discussion forums, and to create rich text using a plain text editor.

## Tables

| Left columns  | Right columns |
| ------------- |:-------------:|
| left foo      | right foo     |
| left bar      | right bar     |
| left baz      | right baz     |

## Blocks of code

```
let message = 'Hello world';
alert(message);
```

## Inline code

This web site is using `markedjs/marked`.

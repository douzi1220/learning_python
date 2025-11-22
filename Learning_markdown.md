> 这是一个引用块
> 可以多行使用
>
> > 嵌套引用
> 
> - 引用中的列表
> - 另一个列表项
>

使用 `printf()` 函数输出文本




```python
def hello_world():
    print("Hello, World!")
    return True
```




```python
def main():
    name = input("请输入你的名字: ")
    age_text = input("请输入你的年龄(数字): ")
    age = int(age_text)
    print(f"你好，{name}！你今年 {age} 岁。")

if __name__ == "__main__":
    main()
```



| 左对齐 | 居中对齐 | 右对齐 |
|:-------|:--------:|-------:|
| 单元格 | 单元格   | 单元格 |
| 数据1  | 数据2    | 数据3  |



- [x] 已完成任务
- [ ] 未完成任务
- [ ] 另一个任务


这是一个带脚注的句子[1](@ref)。

[1](@ref): 这里是脚注内容。


术语一
: 定义一

术语二
: 定义二
: 第二个定义


==高亮文本==



行内公式：$E = mc^2$

块级公式：
$$
\int_{-\infty}^{\infty} e^{-x^2} dx = \sqrt{\pi}
$$

---
layout: post
title:  "Markdown User Guide"
date:   2018-11-10 19:46:36 +0800
categories: markdown
---
# 列表

## 有序列表

1. abc
    1. abc
    2. abc
    3. abc
2. abc
3. abc
4. abc

## 无序列表

- abc
    - abc
    - abc
- abc
- abc
- abc

# 图像

# 表格

# 数学公式

# 代码片段

## C++

{% highlight c++ %}
#include <iostream>
#include <vector>
using namespace std;

int main(int argc, char* argv[])
{
    int a[] = {1,2,3,4,5,6,7,8,9,0};
    vector<int> vec(a,a+sizeof(a)/sizeof(a[0]));
    for(auto it = vec.begin(); it != vec.end(); ++it)
    {
        cout << *it << " ";
    }
    cout << endl;
    return 0;
}
{% endhighlight %}

## Python

{% highlight python %}
# -*- coding:utf-8 -*-
import sys
import os

if __name__ == '__main__':
    print('Hello,Python3!')
{% endhighlight %}

## Java

{% highlight java %}
class HelloWorld
{
    public static void main(String[] args)
    {
    }
}
{% endhighlight %}

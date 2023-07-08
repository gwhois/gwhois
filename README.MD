# gwhois.co - 又一款 Whois 查询（域名查询）工具

市面上有众多的 Whois 查询工具，但它们往往难以满足特定需求。

例如：实时查询注册局与注册商数据，支持尽可能多的域名后缀，还能将关键信息（如注册时间、过期时间、状态、注册人信息等）高亮呈现。

而 [gwhois.co](https://gwhois.co) 正好可以满足以上需求。

![gwhois.co](https://blog.dnleader.com/img/gwhois.co/gwhois-00.png)

## 使用方式

gwhois.co 支持多种形式的查询：

1. [gwhois.co/`google.com`](https://gwhois.co/google.com)（直接在后面拼接待查询的域名）

2. [gwhois.co/`a.b.c.d.google.com`](https://gwhois.co/a.b.c.d.google.com)（支持多级域名）

3. [gwhois.co/`https://www.google.com/a/b/c`](https://gwhois.co/https://www.google.com/a/b/c)（支持URL）

4. [gwhois.co/`hello world`](https://gwhois.co/hello%20world)（甚至是字符串，默认查询 .com）


## 功能特点

1. 实时查询：gwhois.co 所有请求都是实时向注册局和注册商获取的。

2. 数据详尽：一般工具只提供注册局的数据，但 gwhois.co 同时提供注册商的数据。因为很多数据注册局没有提供，但注册商却会提供，这对于数据挖掘来讲很有帮助。例如下面的例子：

![world.com-01](https://blog.dnleader.com/img/gwhois.co/gwhois-01.png)

---

![world.com-02](https://blog.dnleader.com/img/gwhois.co/gwhois-02.png)
注册局没有提供关于注册人的信息。

![world.com-03](https://blog.dnleader.com/img/gwhois.co/gwhois-03.png)
注册商却提供了注册人的详细信息。

---

3. 信息提取：gwhois.co 支持从原始 Whois 数据中提取信息，并将重要信息高亮显示。

![](https://blog.dnleader.com/img/gwhois.co/gwhois-06.png)

4. 后缀多样：gwhois.co 提供尽可能多的后缀支持（现已支持1000+后缀）。

![](https://blog.dnleader.com/img/gwhois.co/gwhois-04.png)

5. 可用支持：gwhois.co 发现域名可用，可立即跳转注册商注册。

![](https://blog.dnleader.com/img/gwhois.co/gwhois-05.png)

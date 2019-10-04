---
title: Khái Niệm Nguyên Lý Kế Toán
permalink: /docs/
redirect_from:
  - /docs/home/
  - /docs/quickstart/
  - /docs/extras/
---
Theo Luật Kế toán: “Kế toán là việc thu thập, xử
lý, kiểm tra, phân tích và cung cấp thông tin kinh tế, tài chính dưới
hình thức giá trị, hiện vật và thời gian lao động”.
Cũng theo Luật Kế toán thì kế toán được chia ra 2 loại là kế toán
tài chính và kế toán quản trị, trong đó:
Kế toán tài chính là việc thu thập, xử lý, kiểm tra, phân tích và
cung cấp thông tin kinh tế, tài chính bằng báo cáo tài chính cho đối
tượng có nhu cầu sử dụng thông tin của đơn vị kế toán. 
Kế toán quản trị là việc thu thập, xử lý, kiểm tra, phân tích và
cung cấp thông tin kinh tế, tài chính theo yêu cầu quản trị và quyết
định kinh tế, tài chính trong nội bộ đơn vị kế toán. Định nghĩa về kế
toán trên nhấn mạnh đến công việc của những người làm công tác kế toán. 

## Instructions

1. Install a full [Ruby development environment](/docs/installation/)
2. Install Jekyll and [bundler](/docs/ruby-101/#bundler) [gems](/docs/ruby-101/#gems)
```
gem install jekyll bundler
```
3. Create a new Jekyll site at `./myblog`
```
jekyll new myblog
```
4. Change into your new directory
```
cd myblog
```
5. Build the site and make it available on a local server
```
bundle exec jekyll serve
```
6. Now browse to [http://localhost:4000](http://localhost:4000){:target="_blank"}

If you encounter any unexpected errors during the above, please refer to the
[troubleshooting](/docs/troubleshooting/#configuration-problems) page or the
already-mentioned [requirements](/docs/installation/#requirements) page, as
you might be missing development headers or other prerequisites.

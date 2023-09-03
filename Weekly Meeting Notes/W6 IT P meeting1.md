**Progress check**

1. docker compose diagram

   

2. database design diagram

   

3. reuse plan

   

4. layered architecture diagram

网站设计功能

比方说客户的要求是

- 要有一栏toolbar 然后要有一个navbar让admin可以随时切换到不同的page

- toolbar旁边就应该是整个网页 然后客户想要直觉式交互 即点击就能更改网页的section 或者内容
- 然后里面的content/event/course..之类的内容都会存放在DB里

Toolbar

Add element

- 文字编辑 ->文字颜色 大小 default的font+我们现在用的font
- 图片编辑 客户可以根据需要 上传他们想要的照片 但是我们会定义一个格式 如果超出格式的大小 要crop size

Change of Subsection

- 让客户可以移动不同的section - 在同一页面内

Navbar

页面换页

Tool bar保持不变
**现有进度**

* Content page主页成型 

  * 包括Nav bar的创建 
  * dropdown menu的创建
  * User login page （没有实际功能）
  * dropdown animation
  * 主content section
  * 三个subsection 的创建
  * Contact section和social media的link

* 对后端有个初步的认知

  * 包括flask的安装（今天全组最好都已经有react和flask的运行环境）

  * axios库 （简化向服务器发送HTTP请求的步骤）

  * flask的login库

    * ```
      //网址 https://flask-login.readthedocs.io/en/latest/
      @app.route('/login//这里放url', methods=['GET', 'POST'])
      def login():
          # Here we use a class of some kind to represent and validate our
          # client-side form data. For example, WTForms is a library that will
          # handle this for us, and we use a custom LoginForm to validate.
          form = LoginForm()
          if form.validate_on_submit():
              # Login and validate the user.
              # user should be an instance of your `User` class
              login_user(user)
      
              flask.flash('Logged in successfully.')
      
              next = flask.request.args.get('next')
              # url_has_allowed_host_and_scheme should check if the url is safe
              # for redirects, meaning it matches the request host.
              # See Django's url_has_allowed_host_and_scheme for an example.
              if not url_has_allowed_host_and_scheme(next, request.host):
                  return flask.abort(400)
      
              return flask.redirect(next or flask.url_for('index'))
          return flask.render_template('login.html', form=form)
      ```

      

**现有的挑战** 

后端的不确定性 ->需要去跟别的组co一下

服务器的具体信息 没有服务器后端做了也没意义

跟我们的网站加点亮点

* debug 测试step

客户需求 我们现在还在很初步的阶段 要时刻跟客户汇报进度 然后确认需求

**分配下一个阶段的工作**

content每个page的layout 做出来

后端 先跟别的组co一下 然后 争取把admin的 dashboard做出来

要跟client无论线上还是线下 组织一个meeting 走一下流程



**然后简单说下明天standup每个人负责的部分**






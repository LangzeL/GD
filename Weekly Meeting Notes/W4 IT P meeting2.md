**Current Progress**

- The main content page has been formed
  - This includes the creation of the Nav bar
  - The creation of the dropdown menu
  - User login page (no actual functionality yet)
  - Dropdown animation
  - The main content section
  - The creation of three sub-sections
  - Contact section and links to social media
- A preliminary understanding of the backend has been established
  - This includes the installation of flask (by today, everyone in the group should ideally have the operating environment for both React and Flask)
  - Axios library (simplifies the steps to send HTTP requests to the server)
  - Flask's login library
    - Here is an example of utilizing flask for user login. The details are mentioned in the code snippet.

* ```
  https://flask-login.readthedocs.io/en/latest/
  @app.route('/login//url', methods=['GET', 'POST'])
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

  

**Current Challenges**

- Uncertainty in the backend -> need to coordinate with other groups
- Specific information about the server is missing; without the server, any backend development is meaningless.
- Adding more features and highlights to our website
- Debugging and testing steps
- Client requirements are still in a very preliminary stage; we need to keep the client updated on the progress regularly and confirm requirements.

**Assignments for the Next Phase**

- Complete the layout for each content page
- For the backend, coordinate with other groups first and then try to develop the admin dashboard
- Arrange a meeting with the client, either online or offline, to walk through the process

**Lastly, let's briefly discuss the parts each person is responsible for in tomorrow's standup.**




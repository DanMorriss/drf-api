## Frontend Readme

[React Bootstrap](https://react-bootstrap-v4.netlify.app/)  
[Adding CSS modules stylesheet](https://create-react-app.dev/docs/adding-a-css-modules-stylesheet/)  
[Using CSS modules to style react components](https://medium.com/@ralph1786/using-css-modules-in-react-app-c2079eadbb87)  
[React router Docs](https://v5.reactrouter.com/web/guides/quick-start)  
[Optional Chaining](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Optional_chaining)  
[Destructuring rules](https://zaiste.net/posts/javascript-destructuring-assignment-default-values/)  
[Inline if with logical && operator](https://legacy.reactjs.org/docs/conditional-rendering.html#inline-if-with-logical--operator)  
[Web API URL's](https://developer.mozilla.org/en-US/docs/Web/API/URL)  
[Create object URL](https://developer.mozilla.org/en-US/docs/Web/API/URL/createObjectURL_static)  
[Revoke object URL](https://developer.mozilla.org/en-US/docs/Web/API/URL/revokeObjectURL_static)  
[Form data class](https://developer.mozilla.org/en-US/docs/Web/API/FormData)  
[Conditional (ternirary) Operator Chaining](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Conditional_Operator#conditional_chains)  
[Infinite Scroll Docs](https://www.npmjs.com/package/react-infinite-scroll-component)  
[Double NOT !!](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Logical_NOT#double_not_!!)  
[React Bootstrap custom dropdown menu](https://react-bootstrap-v4.netlify.app/components/dropdowns/#custom-dropdown-components)  
[Forwarding Refs](https://legacy.reactjs.org/docs/forwarding-refs.html#forwarding-refs-to-dom-components)  
[React Testing Library](https://testing-library.com/docs/react-testing-library/intro/)  
[React Testing Query Methods](https://testing-library.com/docs/queries/about/)  
[Mock Service Worker Docs](https://mswjs.io/docs/)  
[Local Storage](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage)  
[NPM audit](https://docs.npmjs.com/auditing-package-dependencies-for-security-vulnerabilities)  
[React Calendar](https://www.npmjs.com/package/react-calendar)  
[Video example of React Calendar](https://www.youtube.com/watch?v=WutUO81wE90)  

<hr />

`npm install`  
DON'T DO THIS...  
`npm audit fix --force`   
`npm install react-bootstrap@1.6.3 bootstrap@4.6.0`  
`npm install react-router-dom@5.3.0`  
`npm install axios`  
`npm install react-infinite-scroll-component`  
option shift f > format document  
command shipt p > command pallet > Format document  
command shipt p > command pallet > detect indentation from content  
the --save-dev will run it only in the development server (this is for testing)  
`npm install msw --save-dev`  
`npm install --save-dev babel-jest @babel/core`  
`npm install --save-dev @babel/core @babel/preset-env @babel/preset-react babel-jest`  
Delete: package.json, package-lock.json, node modules folder.  
Cope [package.json](https://github.com/Code-Institute-Solutions/moments/blob/master/package.json) from walkthrough  
`npm install`  
This needs to be run each time you open the workspace.  
`nvm install 16 && nvm use 16`  
After adding this code into package.json it should not need the above command to work.  

`  "engines": {
    "node": "16.19.1",
    "npm": "8.19.3"
  }`

`npm install jwt-decode`  
`npm audit`  
`npm audit fix`  

<hr />

## Backend Readme

[Django Rest Framework Docs](https://www.django-rest-framework.org/)  
[Filtering Docs](https://www.django-rest-framework.org/api-guide/filtering/) 
[Django Generics Docs](https://www.django-rest-framework.org/api-guide/generic-views/#attributes/)  
[Django Related Name Docs](https://docs.djangoproject.com/en/3.2/ref/models/fields/#django.db.models.ForeignKey.related_name)  
[Django Unique Together Docs](https://docs.djangoproject.com/en/3.2/ref/models/options/#unique-together)  
[Django Aggregation Docs](https://docs.djangoproject.com/en/3.2/topics/db/aggregation/)  
[Django Annotate() Docs](https://docs.djangoproject.com/en/3.2/ref/models/querysets/#django.db.models.query.QuerySet.annotate)  
[Django Count() Docs](https://docs.djangoproject.com/en/3.2/ref/models/querysets/#django.db.models.Count)  
[Django Combine Multiple Aggregations Docs](https://docs.djangoproject.com/en/3.2/topics/db/aggregation/#combining-multiple-aggregations)  
[JSON Web Token Docs](https://jwt.io/)  
[Django Rest Instillation Doc](https://dj-rest-auth.readthedocs.io/en/latest/installation.html)  
[Django Rest FAQ's](https://dj-rest-auth.readthedocs.io/en/latest/faq.html)  
[Django Rest Framework Date and Time formatting Docs](https://www.django-rest-framework.org/api-guide/settings/#date-and-time-formatting)  
[Python Date and Time formatting Docs](https://docs.python.org/3/library/time.html#time.strftime)  


`python3 -m venv venv`

`source venv/bin/activate`

`pip3 install 'django<4'`

`django-admin startproject drf_api .`

`pip install django-cloudinary-storage`

`pip install Pillow` - Has image processing capabilities needed for this project.

`python3 manage.py startapp profiles`

`python3 manage.py makemigrations`

`python3 manage.py migrate`

`python3 manage.py createsuperuser`

`python3 manage.py runserver`

`pip3 freeze > requirements.txt`

`pip install djangorestframework`

`python3 manage.py startapp posts`

`python3 manage.py test`

`pip install django-filter`

`pip3 install dj-rest-auth==2.1.9`

`pip install 'dj-rest-auth[with_social]'`

`pip install djangorestframework-simplejwt`

`pip3 install dj_database_url==0.5.0 psycopg2`

`python3 manage.py makemigrations --dry-run`

`pip3 install gunicorn django-cors-headers`

[Frontend repo](https://github.com/DanMorriss/moments.git)

`git clone <react_repo_url> frontend`
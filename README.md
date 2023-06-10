# PHP Laravel Extends, Section, Yield => Example View Layout

[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://www.codehafeez.com/)

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/codehafeez/)

[![whatsapp](https://img.shields.io/badge/whatsapp-GREEN?style=for-the-badge&logo=whatsapp&logoColor=white)](https://api.whatsapp.com/send?phone=923123349398)



```bash
# ========================================================
# default.blade.php => code
# ========================================================
<html>
<body>
@yield('header')
@yield('content')
@yield('footer')
</body>
</html>


# ========================================================
# welcome.blade.php => code
# ========================================================
@extends('default')

@section('header')
    <p>View one's header</p>
@endsection

@section('content')
    <p>View one's content</p>
@endsection

@section('footer')
   <p>View one's footer</p>
@endsection
# ======================================================

php artisan serve
```    


## Screenshots
![](https://raw.githubusercontent.com/codehafeez/laravel-example_form-validation-app3/main/Screenshots/Output-01.png)
![](https://raw.githubusercontent.com/codehafeez/laravel-example_form-validation-app3/main/Screenshots/Output-02.png)
![](https://raw.githubusercontent.com/codehafeez/laravel-example_form-validation-app3/main/Screenshots/Output-03.png)
![](https://raw.githubusercontent.com/codehafeez/laravel-example_form-validation-app3/main/Screenshots/Output-04.png)
![](https://raw.githubusercontent.com/codehafeez/laravel-example_form-validation-app3/main/Screenshots/Output-05.png)
![](https://raw.githubusercontent.com/codehafeez/laravel-example_form-validation-app3/main/Screenshots/Output-06.png)
![](https://raw.githubusercontent.com/codehafeez/laravel-example_form-validation-app3/main/Screenshots/Output-07.png)


## 🔗 www.codehafeez.com

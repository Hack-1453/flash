# Flash Framework

<p align="center">
  <img src="docs/flash-logo.png" width="400px" alt="Flash Logo">
</p>

Flash is a high performance, open source web application framework.
Flash web framework follows the MVT (Model-View-Template) architectural pattern or you can say MVC (Model-View-Controller) pattern, because controller is handle by the system.
Flash is fast, lightweight, powerful, simple and easy to use.

Flash allows user to create web applications in easy and simplest way, in Flash framework user can create their own services and library.


## Features

  - Flash is fast and powerful web framework.
  - It's very simple and easy to learn.
  - It is based on MVT Arhitecture.
  - It support custom libraries and services.
  - Easy to create API and Web Services.
  - Easy to deploy on any server.


## Installation

  Flash web framework is for PHP, so it's requires PHP 5.6 or newer. now you won’t need to setup anything just yet.

### Flash can be installed in few steps:

  - [Download](https://github.com/rajkumardusad/flash/archive/master.zip) the Flash files.
  - Unzip the package.
  - Upload all the Flash folders and files (system, application, .htaccess, index.php) on the server.

  That's it, in the Flash web framework there is nothing to configure and setup. it's always ready to go.


## Simple Example

  A simple `Hello, World` web application in Flash web framework.

### Create View

  Let’s write the first view. Open the `app/views.php` file and put the following PHP code in it:

```php
class view extends Views {
  function hello_world() {
    return $this->response("hello, world !!");
  }
}
```

  Hello world view is created now map this view with URLs.

### Map URLs with Views

  Let's create URL and map with views. open `app/urls.php` file and put the following code in it:

```php
//include views to route URLs
require_once("views.php");

$urlpatterns=[
  '/' => 'view.hello_world',
];
```

  Now a simple hello world web app is created.


## Simple Web Api Example

  A simple `Hello, World` web Api in Flash web framework.

### Create View

  Let’s write the first view. Open the `app/views.php` file and put the following PHP code in it:

```php
class view extends Views {
  function hello_world() {
    $data = [
      'status' => true,
      'data' => 'Hello, World',
    ];
    //Send Json Response
    return $this->response_json($data);
  }
}
```

  Hello world view is created now map this view with URLs.

### Map URLs with Views

  Let's create URL and map with views. open `app/urls.php` file and put the following code in it:

```php
//include views to route URLs
require_once("views.php");

$urlpatterns=[
  '/' => 'view.hello_world',
];
```

  Now a simple `Hello, World` web Api is created.


## Documentation

  - **Learn more about Flash from [Documentation](docs/README.md) file.**
  - **Documentation : https://rajkumardusad.github.io/flash**


## License

  [MIT License](LICENSE)

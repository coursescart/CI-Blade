# ci-blade
Laravel blade template engine for Codeigniter 3.0+!
---

# Require
PHP:>=PHP5.4.*

# Use
### 0x0.1 Set cache path:
application/libraries/Blade.php
`$cachePath = APPPATH . 'cache/views'; // view cache directory`


### 0x1.1 Simple use

`$this->blade->view('welcome_message');`

### 0x1.2 Pass vars to template

`$this->blade->view('welcome_message', $vars);`

#Laravel Blade Document
https://laravel.com/docs/5.1/blade

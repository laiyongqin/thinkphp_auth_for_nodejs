# thinkphp auth for nodejs 
一个nodejs的权限认证类，从thinkphp移植过来的。由于代码是按php的思路来的，并且没有写test case，再次是因为没有最终使用。没有完成最终版本，此版本v2是改进了更像php的写法。这个权限经过我的移植发现是可以实现的，如果你有使用请注意两点：

- 此版本可用，需要从数据库取的方法自己实现。
- 登录验证没有完成，只做了实时验证。登录验证只是把权限列表写在session而已。

最后，如果你使用并且完善后可以提交代码。

https://github.com/liu21st/thinkphp/blob/master/ThinkPHP/Library/Think/Auth.class.php
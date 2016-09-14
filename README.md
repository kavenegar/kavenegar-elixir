#Elixir SDK
# <a href="http://kavenegar.com/rest.html">Kavenegar RESTful API Document</a>
If you need to future information about API document Please visit RESTful Document

## Installation
<p>
First of all, You need to make an account on Kavenegar from <a href="https://panel.kavenegar.com/Client/Membership/Register">Here</a>
</p>
<p>
After that you just need to pick API-KEY up from <a href="http://panel.kavenegar.com/Client/setting/index">My Account</a> section.
Here You can download the Elixir SDK <a href="https://github.com/KaveNegar/kavenegar-elixir/archive/master.zip">Here</a> or just pull it.
Anyway there is good tutorial about <a href="http://gun.io/blog/how-to-github-fork-branch-and-pull-request/">Pull  request</a>
</p>
If [available in Hex](https://hex.pm/docs/publish), the package can be installed as:

  1. Add kavenegar to your list of dependencies in `mix.exs`:

        def deps do
          [{:kavenegar, "~> 0.0.1"}]
        end

  2. Ensure kavenegar is started before your application:

        def application do
          [applications: [:kavenegar]]
        end




## Usage
Well, There is an example to Send SMS by Elixir.

```elixir
Kavenegar.send %{receptor: "+989123456789", message: "this is a sample text"}
```
will return:
```elixir
%{"entries" => [%{"cost" => 130, "date" => 1466091791,
     "message" => "this is a sample text", "messageid" => 999999999,
     "receptor" => "+989123456789", "sender" => "10001000010000", "status" => 1,
     "statustext" => "در صف ارسال"}],
  "return" => %{"message" => "تایید شد", "status" => 200}}
```


#Contribution
Bug fixes, docs, and enhancements welcome! Please let us know <a href="mailto:support@kavenegar.com?Subject=SDK" target="_top">support@kavenegar.com</a>



## Persian tutorial / راهنمای فارسی
###راهنما
در صورتی که مایل هستید راهنمای فارسی کیت توسعه کاوه نگار را مطالعه کنید به سفحه 
<a href="http://kavenegar.com/sdk.html">کد ارسال پیامک</a>
مراجعه کنید

###مستندات
<p>
برای مطالعه مستندات کار با 
<a href="http://kavenegar.com"  target="_blank">وب سرویس اس ام اس</a>
کاوه نگار به سفحه <a href="http://kavenegar.com/rest.html">مستندات</a>مراجعه کنید
</p>
###معرفی وب سرویس کاوه نگار
<p>
برای مشاهده ویژگی های 
<a href="http://kavenegar.com/%D9%88%D8%A8-%D8%B3%D8%B1%D9%88%DB%8C%D8%B3-%D9%BE%DB%8C%D8%A7%D9%85%DA%A9.html">
وب سرویس پیامک
</a>
کاوه نگار به صفحه  وب سرویس مراجعه نمائید
</p>
### ایجاد حساب کاربری
<p>
و بالاخره اگر در استفاده از سرویس کاوه نگار مشکلی داشتید یا پیشنهاد همکاری  بود لطفا حتما به ما اطلاع دهید
<br>
<a href="mailto:support@kavenegar.com">support@kavenegar.com</a>

</p>

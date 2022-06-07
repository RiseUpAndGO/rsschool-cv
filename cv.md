# Igor Burkov


### Contact information:
**Phone:** 
**E-mail:** example@gmail.com
**Telegram:** @burkovigor


### About myself:
I want to learn front-end development skills in **RS-SCHOOL**


### Skills:
+ HTML5 Basics
+ PHP
+ Git, GitHub
+ PHPStorm, VScode


### Code example:
***KATA from Codewars:*** *Complete the method/function so that it converts dash/underscore delimited words into camel casing. The first word within the output should be capitalized only if the original word was capitalized (known as Upper Camel Case, also often referred to as Pascal case).*

```
function toCamelCase($str)
{
  $result = preg_replace_callback('#[_|-](\S{1})#', function($match) {
    return strtoupper($match[1]);
  }, $str);
  return $result;
}
```

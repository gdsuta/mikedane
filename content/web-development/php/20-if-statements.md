---
date: 2017-11-15T17:52:38-05:00
title: "If Statements"
seo_title: "If Statements | PHP | Giraffe Academy"
subheader:
     greeting: PHP - Programming Language
     description: This course covers the basics of programming in PHP. Work your way through the videos and we'll teach you everything you need to know to start your programming journey!
description: This tutorial covers if statements in PHP.
author: Mike Dane
image: if-statements.png
video: KU8jKqn1-HQ
url: /web-development/php/if-statements/
weight: 20
---

## Code

{{< code lang="php" >}}
$isStudent = false;
$isSmart = false;

if($isStudent && $isSmart){
     echo "You are a student";
} elseif($isStudent && !$isSmart){
     echo "You are not a smart student";
} else {
     echo "You are not a student and not smart";
}
echo "<br>";

// >, <, >=, <=, !=, ==
if(1 > 3){
     echo "number comparison was true";
}
echo "<br>";

if("dog" == "cat"){
   echo "string comparison was true";
}
{{< /code >}}
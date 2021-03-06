---
id: 587d7db7367417b2b2512b9e
title: 匹配字符串的末尾
challengeType: 1
forumTopicId: 301352
---

# --description--

在上一个挑战中，学习了使用`^`符号来搜寻字符串开头的匹配模式。还有一种方法可以搜寻字符串末尾的匹配模式。

可以使用正则表达式的`美元`符号`$`来搜寻字符串的结尾。

```js
let theEnding = "This is a never ending story";
let storyRegex = /story$/;
storyRegex.test(theEnding);
// Returns true
let noEnding = "Sometimes a story will have to end";
storyRegex.test(noEnding);
// Returns false

```

# --instructions--

使用`$`在字符串`caboose`的末尾匹配`"caboose"`。

# --hints--

你应该在正则表达式使用美元符号`$`来搜寻`'caboose'`。

```js
assert(lastRegex.source == 'caboose$');
```

你的正则表达式不应该使用任何标志。

```js
assert(lastRegex.flags == '');
```

你应该在字符串`'The last car on a train is the caboose'`的末尾匹配`'caboose'`。

```js
assert(lastRegex.test('The last car on a train is the caboose'));
```

# --solutions--


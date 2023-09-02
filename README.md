///////// Header /////////

Usage:

```
# A first-level heading
## A second-level heading
### A third-level heading
```

Result:

# A first-level heading
## A second-level heading
### A third-level heading





</br></br></br></br></br></br>///////// Strikethrough /////////

Usage:

```
<s>hello world</s>
```

Result:

<s>hello world</s>

</br></br></br></br></br></br>///////// Commented text /////////
```
<!-- This content will not appear in the rendered Markdown -->
<!-- Commented text -->
```
Result:
<!-- This content will not appear in the rendered Markdown -->


</br></br></br></br></br></br>///////// Task Lists /////////
```
- [x] task 1

- [ ] task 2
```

- [x] task 1

- [ ] task 2

</br></br></br></br></br></br>///////// Insert image /////////

Image hostings:

https://imgur.com/

https://img.hurtom.com/


Usage: 

Insert original size:

```
[![enter image description here][1]][1]

[1]: https://i.stack.imgur.com/tnpHr.jpg
```

Insert with changed size:

```
[![enter image description here][1]][1]

[1]: https://i.stack.imgur.com/tnpHr.jpg?s=16
[2]: https://i.stack.imgur.com/tnpHr.jpg?s=32
[3]: https://i.stack.imgur.com/tnpHr.jpg?s=64
[4]: https://i.stack.imgur.com/tnpHr.jpg?s=128
[5]: https://i.stack.imgur.com/tnpHr.jpg?s=256
[6]: https://i.stack.imgur.com/tnpHr.jpg?s=512
```

[![enter image description here][1]][1]

[![enter image description here][2]][2]

[1]: https://i.stack.imgur.com/tnpHr.jpg?s=64
[2]: https://i.stack.imgur.com/tnpHr.jpg?s=128


also you can use `<img> html tag`

```
<img src="https://i.stack.imgur.com/tnpHr.jpg" width="220" height="60">
```
<img src="https://i.stack.imgur.com/tnpHr.jpg" width="220" height="60">





</br></br></br></br></br></br>///////// Embed video /////////

Just insert direct link to mp4 video:

```
https://user-images.githubusercontent.com/1991296/224442907-7693d4be-acaa-4e01-8b4f-add84093ffff.mp4
```

or just insert direct link on youtube:

```
<video src='your URL here' width=180/>
```

<video src="https://drive.google.com/uc?export=download&id=1YBta3aHQGKrGPlgan5RLz-UZUqI7VwRg" type='video/mp4'></video>

also we can share video using special repo: https://www.geeksforgeeks.org/how-to-add-videos-on-readme-md-file-in-a-github-repository/?id=discuss 
and after this use it inside of any ReadMe from other repositories

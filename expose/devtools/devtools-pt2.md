<img width="1152" alt=" result-calculateSum" src="https://user-images.githubusercontent.com/91338627/137637000-a6ff2714-5c6d-4e6e-91c1-45b61672729e.png">
<img width="1152" alt="result-dataType" src="https://user-images.githubusercontent.com/91338627/137637016-237da492-8a97-428c-9956-253e2bc31017.png">

1. The bug is that num1 and num2 are strings, but they should be converted to numbers.
2. In order to fix this issue, we should convert these two strings to numbers, that is using parseInt() to convert, so the fixed equation should be <br>
let result = parseInt(num1) + parseInt(num2), that is the type of result also should be a number.

<h1>by team c4</h1>
<h2>enc.py :</h2>
<b>It's native Cython, meaning a file is converted directly into Cython with all the functions and everything</b>

<h2>enc2.py :</h2>
<b>It is cython and is not converted directly. This means that before converting to cython, it is encrypted using Base64. After that, the cipher text is divided into parts to make it difficult for a hacker to decode the code.
The reason for using this method is that Cyton fails to convert some times due to strange formatting of text and symbols</b>

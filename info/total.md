>"Where does a wise man hide a leaf? In the forest.
>But what does he do if there is no forest? ... He grows a forest to hide it in."

>-- Gilbert Keith Chesterton

Have you ever tried to send a secret message to someone without using the encrypted channel? 
You could conceivably use the public communication channels to tell your secret.
Even if someone finds your message, it’s easy to just brush them off and tell them it's paranoia or some bogus conspiracy.
That's why we're goingt to try and use this method for squad communication.

You are given a chunk of text. Gather all of the capital letters in one word in the order that they appear in the text.

For example: text = "**H**ow are you? **E**h, ok. **L**ow or **L**ower? **O**hhh.",
if we collect all of the capital letters, we get the message "HELLO".

**Input:** A chunk of text as a string. 

**Output:** The secret message as a string or an empty string.

**Example:**

```python
find_message("How are you? Eh, ok. Low or Lower? Ohhh.") == "HELLO"
find_message("hello world!") == ""
```
**How it is used:**

This type of communication has been used to send secret messages, or even tell jokes.
But the skills behind it show you how to find specific types of information or patterns hidden within
larger chunks of data that would be difficult to find by hand.

**Precondition:**
```python
0 < len(text) <= 1000
all(ch in string.printable for ch in text)
```

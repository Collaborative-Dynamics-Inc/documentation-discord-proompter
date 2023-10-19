# Chatbot - Textfile Injection

> Due to the low character limit of Discord, our Chatbots are able to handle text file attachments. Theres no fancy magic going on with vector storage or something else. It's as simple as replacing a placeholder with the content of the attachment. Therefore it's unnecessary to mention anything like "read the textfile" or similar, as, from the chatbots POV, it's treated as if you would have written the text in your message

### Example
> We have two text files we want to compare. The names of those files are not important, but they have to be `.txt` format. We call them `file_1.txt` and `file_2.txt`
> The placeholder looks like this: `%tf_N%` where `N` is the number of the file when they are added as attachment to the Discord Message. You can count them from left to right in the attachment list above the chatbox to get the number
> Our input would be something like this:
```yaml
Please compare the following two texts and make a list of all the differences
Text 1: %tf_1%
Text 2: %tf_2%
```
> What happens behind the scenes is, `%tf_1%` gets replaced with the content of the first file, the one at the left. `%tf_2` gets replaced with the content of the second uploaded file, the one on the right side*

> The example might give the implication that you need to say things like "Text 1:", but thats not the case. You don't need to follow any specific format.


## Note
> Each file number can only be used once in every file. You cannot have `%tf_1%` twice in the same message

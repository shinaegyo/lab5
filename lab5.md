``` 
Part 1: Debugging Scenario
 ```

1)
Dear Mr. Shin,

I hope you are doing well during these times. I am having trouble with the `reversed` method in the ArrayExamples.java file. It says that I have an error in my `testReverse2` method. Can you help me
with this issue because I have been debugging it for a long time and I still have not figured out the issue.

Best, 

Patrick

`terminal`

<img width="668" alt="terminal screenshot pt 1" src="https://github.com/shinaegyo/lab5/assets/137027086/7b34773b-39a2-424d-8c03-421ab9b21706">

`test method `

<img width="493" alt="test method pt 1" src="https://github.com/shinaegyo/lab5/assets/137027086/e9d1e5f9-0aad-43d5-a224-b53e235a17a6">

`revered method SS`

<img width="443" alt="reversed method pt 1" src="https://github.com/shinaegyo/lab5/assets/137027086/2601dd75-9f8c-46d4-90b8-03f31d069f71">


2)

Hello Patrick,

Yeah I am looking at your code right now and you have one minor error. In the `reversed` method, line 32 seems to have an error. Whenever you want to reverse the order of the list, you should try to
subtract it with another variable that will help reverse the order. I suggest you try to insert `-i` next the `arr.length` in addition with your `-1`. 

Best,

Mr.Shin

3)

`Output of Terminal`

<img width="340" alt="Screen Shot 2023-12-03 at 10 24 33 PM" src="https://github.com/shinaegyo/lab5/assets/137027086/ad8f236a-11fa-4cf5-bfd6-691689f77170">

The bug was in line 32 as suggested by the TA. There needed to be `-i` in addition with the `-1` 

4)

`The file & directory structure needed`

<img width="174" alt="Screen Shot 2023-12-03 at 10 33 58 PM" src="https://github.com/shinaegyo/lab5/assets/137027086/6182d379-ef20-4052-a97f-8ce333a7537e">

`The contents of each file before fixing the bug`

<img width="717" alt="Screen Shot 2023-12-03 at 10 35 12 PM" src="https://github.com/shinaegyo/lab5/assets/137027086/4ab44099-7682-4888-82f0-e04df151e140">

<img width="538" alt="Screen Shot 2023-12-03 at 10 35 39 PM" src="https://github.com/shinaegyo/lab5/assets/137027086/ad271324-8f31-44a9-bc77-1b6999e875b8">

`The full command line (or lines) you ran to trigger the bug`

<img width="708" alt="Screen Shot 2023-12-03 at 10 36 43 PM" src="https://github.com/shinaegyo/lab5/assets/137027086/863ec690-1be5-4892-8d92-174ad7eaa53c">

`A description of what to edit to fix the bug`

To edit the bug, the student should have incorporated `-i` next to arr.length to have the `reversed` method work properly. Not including the `-i` will have every output be the output of the last element. For example in the student's case of
`{4,5,6,7}`, the resulting output would be `{7,7,7,7}` and it would not give an output in reversed order. 




``` 
Part 2: Reflection
```

A cool technical thing I learned about was the VIM commands. The ability the create and edit text files when entering vim in insert and command mode was truly intriguing.
Learning VIM helped me quickly and efficiently locate text because it is a powerful tool. Another technical thing is the use of the git commands. Git add, git commit, and git push all to 
help me in the future when I work with future co-workers.

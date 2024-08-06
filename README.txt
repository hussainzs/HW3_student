Describe how, if at all, you used generative AI to assist with completing this homework.  Recall that you cannot use generative AI to write your SQL queries, but can use it to explain concepts or assist with coding. Please see the statement on generative AI at the top of the homework writeup.

Answer here: I used AI in backend to findout how to add values into SQL queries properly because simply doing ${}$ was giving me errors when the information inside was string. 
I learned that you can use %${}$% or a better approach is to use ? in your SQL query and then provide the information as a parameter in an array. This also prevents SQL injections. 
In the frontend, I was having trouble understanding the syntax for Modals, renderCell and some other details which I asked AI to explain to me. I also asked it to teach me what parameters are expected and what they mean. 
I also asked it to explain to me how the structure of different components work in MUI. Finally, I was getting this error in multiple files "ERROR in ./src/components/LazyTable.js 7:0-45"
I asled AI to explain to me and then I commented out the import statement: import { set } from '../../../server/server'; Hopefully that doesnt cause any issues.

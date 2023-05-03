Download Link: https://assignmentchef.com/product/solved-cs372-homework-3-search-the-internet-or-available-corpora-for-sentences-in-english
<br>
In the previous homework assignments, we searched for relevant pairs of information, such as (extol, praise highly), or (dead, center). For this homework, we will look into heteronyms and their pronunciations. A heteronym is “one of two or more homographs (such as a bass voice and bass, a fish) that differ in pronunciation and meaning” (Merriam-Webster Dictionary). Heteronyms may have the same parts-of-speech, as in bass (N), bow (V), tear (N), tear (V), wind (N), and wind (V), but they may also have different parts-of-speech, as in address (N, V), bass (Adj, N), conduct (N, V), frequent (Adj, V), rebel (N, V), tear (N, V) and wind (N, V).

The goal in this homework is first to search the internet or available corpora for <u>sentences in English</u> in which two or more heteronyms appear, and second to give <u>pronouncing annotations</u> to such heteronyms. Your program is supposed to output cited (i.e., together with the source information, such as the Brown Corpus, Times Live) sentences with suitable annotations on heteronyms, together with a CSV file that contains a ranked list of 30 cited sentences with annotations, where the ranking is computed as follows (with precedence 1&gt;2&gt;3):

<ol>

 <li>Higher ranking is given to those sentences that contain more occurrences of the homographs, such as wind + wind + tear + tear, than to those sentences that contain fewer, such as wind + wind + tear.</li>

 <li>Higher ranking is given to those sentences that contain multiple occurrences of homographs, such as wind + wind, than those sentences that contain heteronyms but not homographs, such as wind + tear.</li>

 <li>Higher ranking is given to those sentences that contain heteronyms with the same part-of-speech information, such as tear + tear, than those with different part-of-speech information, such as PROduce + proDUCE.</li>

</ol>

You can devise your own ranking for all the other cases, such as preferring shorter sentences and/or sentences from the internet.




As before, you should use techniques that can be implemented in Python and NLTK.

<ul>

 <li><u>Write a Python code</u> to access the internet and to output cited sentences with annotations.</li>

 <li><u>Include the first 30 sentences</u> in an order as described above.</li>

 <li><u>Discuss your results</u>, to explain how you addressed the goal, and to suggest how you can improve the quality of the results further. This document must be in English.</li>

</ul>

All the requirements as underlined above must be composed by yourself and without help from anyone else. Any similarity of the results will be flagged for plagiarism and, if found sufficiently similar, penalized, up to, but not limited to, a failure to this homework
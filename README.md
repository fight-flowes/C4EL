# C4EL
A novel parallel corpus comprising two semantically equivalent datasets: a Latin-English code-mixed corpus (C4EL.LE) and its monolingual English counterpart (C4EL.EN). 


<h1 style="fontsize: 16">Construction process of C4EL (C4EL.LE and C4EL.EN).</h1>
The metadata (C4.EN) consists of three components for each entry: text, timestamp, and URL. Through the matching process, judging whether Latin phrases in text can obtain new dataset entries, each containing text, timestamp, language, phrase, and URL, where the phrase denotes the collection of Latin phrases present in the text. Based on C4EL.LE, using LLMs to infer new English text, and using BGE-M3 calculate the similarity score of two sentences, create the unit of C4EL.EN.
<img src="https://github.com/fight-flowes/C4EL/blob/main/C4.EN%20to%20%20C4EL.svg" />


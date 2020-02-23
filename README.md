# Commonsense-Paper-List
A summary of must-read papers for Commonsense

- Contributed by **[Jingyun Xu]**.

## [Content](#content)

<table>
<tr><td colspan="2"><a href="#survey-papers">1. Survey</a></td></tr> 
<tr><td colspan="2"><a href="#commonsense-knowledge-Acquisition">2. Commonsense Knowledge Acquisition</a></td></tr>
<tr>
    <td>&emsp;<a href="#Commonsense-Knowledge-Generation">2.1 Commonsense Knowledge Generation</a></td>
    <td><a href="#Commonsense-Knowledge-Updating">2.2 Commonsense Knowledge Updating</a></td>
</tr>
<tr><td colspan="2"><a href="#Commonsense-Making-and-Explanation">3. Commonsense Making and Explanation</a></td></tr> 
<tr><td colspan="2">&emsp;<a href="#Direct-Sense-Making-and-Explanation">3.1 Direct Sense Making and Explanation</a></td></tr>
<tr><td colspan="2">&emsp;<a href="#Indirect-Sense-Making">3.2 Indirect Sense Making</a></td></tr>
    <tr>
    <td colspan="2">&emsp;&emsp;<a href="#Representation">3.2.1 Representation</a></td>
</tr>
    <tr>
    <td>&emsp;&emsp;&emsp;<a href="#Pre-trained-Language-Models">3.2.1.1 Pre-trained Language Models</a></td>
    <td><a href="#Event-Representation">3.2.1.2 Event Representation</a></td>
</tr>
        <tr>
    <td colspan="2">&emsp;&emsp;<a href="#Specific-Task">3.2.2 Specific Tasks</a></td>
</tr>
    <tr>
    <td colspan="2">&emsp;&emsp;&emsp;<a href="#Commonsense-Reasoning">3.2.2.1 Commonsense Reasoning</a></td>
</tr>
        <tr>
    <td>&emsp;&emsp;&emsp;<a href="#Textual-Commonsense-Reasoning">3.2.2.1.1 Textual Commonsense Reasoning</a></td>
    <td><a href="#Visual-Commonsense-Reasoning">3.2.2.1.2 Visual Commonsense Reasoning</a></td>
</tr>
    <tr><td>&emsp;&emsp;&emsp;<a href="#Commonsense-Question-Answering">3.2.2.2 Commonsense Question Answering</a></td>
    <td><a href="#Commonsense-Reading-Comprehension">3.2.2.3 Commonsense Reading Comprehension</a></td></tr>
        <tr><td>&emsp;&emsp;&emsp;<a href="#Understanding-of-Commonsense-Stories">3.2.2.4 Understanding of Commonsense Stories</a></td>
            <td><a href="#Sentiment-Analysis">3.2.2.5 Sentiment Analysis</a></tr>
       <tr><td>&emsp;&emsp;&emsp;<a href="#Dialogue">3.2.2.6 Dialogue </a></td>
       <td><a href="#Abstractive-Summarization">3.2.2.7 Abstractive Summarization</a></td></tr>
     <tr><td colspan="2">&emsp;&emsp;&emsp;<a href="#Text-Generation">3.2.2.8 Text Generation</a></td>
</tr>
   <tr>  <td colspan="2">&emsp;&emsp;&emsp;<a href="#Others">3.2.2.9 Others</a></td></tr>
        <tr>
    <td>&emsp;&emsp;&emsp;<a href="#Textual Taks">3.2.2.9.1 Textual Tasks</a></td>
    <td><a href="#Visual Tasks">3.2.2.9.2 Visual Tasks</a></td>
</tr>
</table>

## [Survey papers](#content)

## [Commonsense Knowledge Acquisition](#content)   
How to generate knowledge, from scratch (Commonsense Knowledge Generation) ? or based on existed ones (Commonsense Knowledge Updating) ?
### [Commonsense Knowledge Generation](#content)
1. **ATOMIC: An Atlas of Machine Commonsense for If-Then Reasoning.** AAAI, 2019. [paper](https://aaai.org/ojs/index.php/AAAI/article/view/4160) [dataset](https://homes.cs.washington.edu/~msap/atomic/)
    
    *Maarten Sap, Ronan Le Bras, Emily Allaway, Chandra Bhagavatula, Nicholas Lourie, Hannah Rashkin, Brendan Roof, Noah A. Smith, Yejin Choi.* 

This is a commonsense knowledge base, which cares about the If-Then relations.
2. **CA-EHN: Commonsense Word Analogy from E-HowNet.** arxiv, 2019. [paper](https://arxiv.org/abs/1908.07218) [dataset](https://github.com/jacobvsdanniel)
    
    *Peng-Hsuan Li, Tsan-Yu Yang, Wei-Yun Ma.* 
Actually, I don not get the dataset. -- 2020.2.23
3. **A Logical Model for Supporting Social Commonsense Knowledge Acquisition.** arxiv, 2019. [paper](https://arxiv.org/abs/1912.11599) [dataset](https://homes.cs.washington.edu/~msap/atomic/)
    
    *Maarten Sap, Ronan Le Bras, Emily Allaway, Chandra Bhagavatula, Nicholas Lourie, Hannah Rashkin, Brendan Roof, Noah A. Smith, Yejin Choi.* 
4. **Automatic Extraction of Commonsense LocatedNear Knowledge.** ACL, 2018. [paper](https://www.aclweb.org/anthology/P18-2016/) [dataset&code](https://github.com/adapt-sjtu/commonsense-locatednear)
    
    *Frank F. Xu, Bill Y. Lin, Kenny Q. Zhu.* 
5. **A Logical Model for Supporting Social Commonsense Knowledge Acquisition.** arxiv, 2019. [paper](https://arxiv.org/abs/1912.11599) [dataset](https://homes.cs.washington.edu/~msap/atomic/)
    
    *Maarten Sap, Ronan Le Bras, Emily Allaway, Chandra Bhagavatula, Nicholas Lourie, Hannah Rashkin, Brendan Roof, Noah A. Smith, Yejin Choi.* 
6. **A Logical Model for Supporting Social Commonsense Knowledge Acquisition.** arxiv, 2019. [paper](https://arxiv.org/abs/1912.11599) [dataset](https://homes.cs.washington.edu/~msap/atomic/)
    
    *Maarten Sap, Ronan Le Bras, Emily Allaway, Chandra Bhagavatula, Nicholas Lourie, Hannah Rashkin, Brendan Roof, Noah A. Smith, Yejin Choi.* 
7. **A Logical Model for Supporting Social Commonsense Knowledge Acquisition.** arxiv, 2019. [paper](https://arxiv.org/abs/1912.11599) [dataset](https://homes.cs.washington.edu/~msap/atomic/)
    
    *Maarten Sap, Ronan Le Bras, Emily Allaway, Chandra Bhagavatula, Nicholas Lourie, Hannah Rashkin, Brendan Roof, Noah A. Smith, Yejin Choi.* 
    
### [Commonsense Knowledge Updating](#content)

## [Commonsense Making and Explanation](#content)   
### [Direct Sense Making and Explanation](#content)
### [Indirect Sense Making](#content)
#### [Representation](#content)
##### [Pre-trained Language Models](#content)
##### [Event Representation](#content)
#### [Specific Tasks](#content)
##### [Commonsense Reasoning](#content)
###### [Textual Commonsense Reasoning](#content)
###### [Visual Commonsense Reasoning](#content)
##### [Commonsense Question Answering](#content)
##### [Commonsense Reading Comprehension](#content)
##### [Understanding of Commonsense Stories](#content)
##### [Sentiment Analysis](#content)
##### [Dialogue](#content)
##### [Abstractive Summarization](#content)
##### [Text Generation](#content)
##### [Others](#content)
###### [Textual Tasks](#content)
###### [Visual Tasks](#content)

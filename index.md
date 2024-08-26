---
bibliography:
- report/references.bib
---

::: titlepage
::: center
University of Reading\
Department of Computer Science\

Computer Science Undergraduate Report Template and Report Writing Guide

 \
FirstName(s) LastName \
*Supervisor:* Supervisor's Name\
A report submitted in partial fulfilment of the requirements of\
the University of Reading for the degree of\
Bachelor of Science in *Computer Science*\

2024-08-26
:::
:::

# Declaration {#declaration .unnumbered}

I, Firstname(s) Lastname, of the Department of Computer Science,
University of Reading, confirm that this is my own work and figures,
tables, equations, code snippets, artworks, and illustrations in this
report are original and have not been taken from any other person's
work, except where the works of others have been explicitly
acknowledged, quoted, and referenced. I understand that if failing to do
so will be considered a case of plagiarism. Plagiarism is a form of
academic misconduct and will be penalised accordingly.\
I give consent to a copy of my report being shared with future students
as an exemplar.\
I give consent for my work to be made available more widely to members
of UoR and public with interest in teaching, learning and research.  \

::: flushright
Firstname(s) Lastname

2024-08-26
:::

# Abstract {#abstract .unnumbered}

This is an undergraduate project report template and instruction on how
to write a report. It also has some useful examples to use LaTeX. Do
read this template carefully. The number of chapters and their titles
may vary depending on the type of project and personal preference.
Section titles in this template are illustrative should be updated
accordingly. For example, sections named "A section\..." and "Example of
\..." should be updated. The number of sections in each chapter may also
vary. This template may or may not suit your project. Discuss the
structure of your report with your supervisor.

 \
**Guidance on abstract writing:** An abstract is a summary of a report
in a single paragraph up to a maximum of 250 words. An abstract should
be self-contained, and it should not refer to sections, figures, tables,
equations, or references. An abstract typically consists of sentences
describing the following four parts: (1) introduction (background and
purpose of the project), (2) methods, (3) results and analysis, and (4)
conclusions. The distribution of these four parts of the abstract should
reflect the relative proportion of these parts in the report itself. An
abstract starts with a few sentences describing the project's general
field, comprehensive background and context, the main purpose of the
project; and the problem statement. A few sentences describe the
methods, experiments, and implementation of the project. A few sentences
describe the main results achieved and their significance. The final
part of the abstract describes the conclusions and the implications of
the results to the relevant field.

 \
**Keywords:** a maximum of five keywords/keyphrase separated by commas

**Report's total word count:** we expect a maximum of 20,000 words
(excluding reference and appendices) and about 50 - 60 pages. \[A good
project report can also be written in approximately 10,000 words.\]

# Acknowledgements {#acknowledgements .unnumbered}

An acknowledgements section is optional. You may like to acknowledge the
support and help of your supervisor(s), friends, or any other person(s),
department(s), institute(s), etc. If you have been provided specific
facility from department/school acknowledged so.

## List of Abbreviations

::: abbrv
School of Mathematical, Physical and Computational Sciences
:::

# Introduction {#ch:into}

**Guidance on introduction chapter writing:** Introductions are written
in the following parts:

-   A brief description of the investigated problem.

-   A summary of the scope and context of the project, i.e., what is the
    background of the
    topic/problem/application/system/algorithm/experiment/research
    question/hypothesis/etc. under
    investigation/implementation/development \[whichever is applicable
    to your project\].

-   The aims and objectives of the project.

-   A description of the problem and the methodological approach adopted
    to solve the problem.

-   A summary of the most significant outcomes and their
    interpretations.

-   Organization of the report.

Consult **your supervisor** to check the content of the introduction
chapter. In this template, we only offer basic sections of an
introduction chapter. It may not be complete and comprehensive. Writing
a report is a subjective matter, and a report's style and structure
depend on the "type of project" as well as an individual's preference.
This template suits the following project paradigms:

1.  software engineering and software/web application development;

2.  algorithm implementation, analysis and/or application;

3.  science lab (experiment); and

4.  pure theoretical development (not mention extensively).

Use only a single **font** for the body text. We recommend using a clean
and electronic document friendly font like **Arial** or **Calibri** for
MS-word (If you create a report in MS word). If you use this template,
DO NOT ALTER the template's default font "amsfont default computer
modern". The default LaTeX font "computer modern" is also acceptable.

The recommended body text **font size** is minimum **11pt** and minimum
one-half line spacing. The recommended figure/table caption font size is
minimum 10pt. The footnote[^1] font size is minimum 8pt. DO NOT ALTER
the font setting of this template.

## Background {#sec:into_back}

Describe to a reader the context of your project. That is, what is your
project and what its motivation. Briefly explain the major theories,
applications, and/or products/systems/algorithms whichever is relevant
to your project.

**Cautions:** Do not say you choose this project because of your
interest, or your supervisor proposed/suggested this project, or you
were assigned this project as your final year project. This all may be
true, but it is not meant to be written here.

## Problem statement {#sec:intro_prob_art}

This section describes the investigated problem in detail. You can also
have a separate chapter on "Problem articulation." For some projects,
you may have a section like "Research question(s)" or "Research
Hypothesis" instead of a section on "Problem statement.'

## Aims and objectives {#sec:intro_aims_obj}

Describe the "aims and objectives" of your project.

**Aims:** The aims tell a read what you want/hope to achieve at the end
of the project. The aims define your intent/purpose in general terms.

**Objectives:** The objectives are a set of tasks you would perform in
order to achieve the defined aims. The objective statements have to be
specific and measurable through the results and outcome of the project.

## Solution approach {#sec:intro_sol}

Briefly describe the solution approach and the methodology applied in
solving the set aims and objectives.

Depending on the project, you may like to alter the "heading" of this
section. Check with you supervisor. Also, check what subsection or any
other section that can be added in or removed from this template.

### A subsection 1 {#sec:intro_some_sub1}

You may or may not need subsections here. Depending on your project's
needs, add two or more subsection(s). A section takes at least two
subsections.

### A subsection 2 {#sec:intro_some_sub2}

Depending on your project's needs, add more section(s) and
subsection(s).

#### A subsection 1 of a subsection {#sec:intro_some_subsub1}

The command \\subsubsection{} creates a paragraph heading in LaTeX.

#### A subsection 2 of a subsection {#sec:intro_some_subsub2}

Write your text here\...

## Summary of contributions and achievements {#sec:intro_sum_results}

Describe clearly what you have done/created/achieved and what the major
results and their implications are.

## Organization of the report {#sec:intro_org}

Describe the outline of the rest of the report here. Let the reader know
what to expect ahead in the report. Describe how you have organized your
report.

**Example: how to refer a chapter, section, subsection**. This report is
organised into seven chapters.
Chapter [2](#ch:lit_rev){reference-type="ref" reference="ch:lit_rev"}
details the literature review of this project. In
Section [3](#ch:method){reference-type="ref" reference="ch:method"}\...

**Note:** Take care of the word like "Chapter," "Section," "Figure" etc.
before the LaTeXcommand \\ref{}. Otherwise, a sentence will be
confusing. For example, In [2](#ch:lit_rev){reference-type="ref"
reference="ch:lit_rev"} literature review is described. In this
sentence, the word "Chapter" is missing. Therefore, a reader would not
know whether 2 is for a Chapter or a Section or a Figure.

# Literature Review {#ch:lit_rev}

A literature review chapter can be organized in a few sections with
appropriate titles. A literature review chapter might contain the
following:

1.  A review of the state-of-the-art (include theories and solutions) of
    the field of research.

2.  A description of the project in the context of existing literature
    and products/systems.

3.  An analysis of how the review is relevant to the intended
    application/system/problem.

4.  A critique of existing work compared with the intended work.

Note that your literature review should demonstrate the significance of
the project.

## Example of in-text citation of references in LaTeX

The references in a report relate your content with the relevant
sources, papers, and the works of others. To include references in a
report, we *cite* them in the texts. In MS-Word, EndNote, or MS-Word
references, or plain text as a list can be used. Similarly, in LaTeX,
you can use the "thebibliography" environment, which is similar to the
plain text as a list arrangement like the MS word. However, In LaTeX,
the most convenient way is to use the BibTex, which takes the references
in a particular format \[see references.bib file of this template\] and
lists them in style \[APA, Harvard, etc.\] as we want with the help of
proper packages.

These are the examples of how to *cite* external sources, seminal works,
and research papers. In LaTeX, if you use "**BibTex**" you do not have
to worry much since the proper use of a bibliographystyle package like
"agsm for the Harvard style" and little rectification of the content in
a BiBText source file \[In this template, BibTex are stored in the
"references.bib" file\], we can conveniently generate a reference style.

Take a note of the commands \\cite{} and \\citep{}. The command \\cite{}
will write like "Author et al. (2019)" style for Harvard, APA and
Chicago style. The command \\citep{} will write like "(Author et al.,
2019)." Depending on how you construct a sentence, you need to use them
smartly. Check the examples of **in-text citation** of sources listed
here \[This template recommends the **Harvard style** of referencing.\]:

-   [@lamport1994latex] has written a comprehensive guide on writing in
    LaTeX \[Example of \\cite{} \].

-   If LaTeX is used efficiently and effectively, it helps in writing a
    very high-quality project report [@lamport1994latex]  \[Example of
    \\citep{} \].

-   A detailed APA, Harvard, and Chicago referencing style guide are
    available in [@uor_refernce_style].

Example of a numbered list:

1.  [@lamport1994latex] has written a comprehensive guide on writing in
    LaTeX.

2.  If LaTeXis used efficiently and effectively, it helps in writing a
    very high-quality project report [@lamport1994latex].

## Example of "risk" of unintentional plagiarism

Using other sources, ideas, and material always bring with it a risk of
unintentional plagiarism.

**MUST**: do read the university guidelines on the definition of
plagiarism as well as the guidelines on how to avoid
plagiarism [@uor_plagiarism].

## Critique of the review

Describe your main findings and evaluation of the literature.  \

## Summary

Write a summary of this chapter \

# Methodology {#ch:method}

We mentioned in Chapter [1](#ch:into){reference-type="ref"
reference="ch:into"} that a project report's structure could follow a
particular paradigm. Hence, the organization of a report (effectively
the Table of Content of a report) can vary depending on the type of
project you are doing. Check which of the given examples suit your
project. Alternatively, follow your supervisor's advice.

## Examples of the sections of a methodology chapter

A general report structure is summarised (suggested) in
Table [3.1](#tab:gen_template){reference-type="ref"
reference="tab:gen_template"}.
Table [3.1](#tab:gen_template){reference-type="ref"
reference="tab:gen_template"} describes that, in general, a typical
report structure has three main parts: (1) front matter, (2) main text,
and (3) end matter. The structure of the front matter and end matter
will remain the same for all the undergraduate final year project
report. However, the main text varies as per the project's needs.

::: {#tab:gen_template}
  ------------- ----------- ----------------------------- --
  Frontmatter               Title Page                    
                            Abstract                      
                            Acknowledgements              
                            Table of Contents             
                            List of Figures               
                            List of Tables                
                            List of Abbreviations         
                                                          
  Main text     Chapter 1   Introduction                  
                Chapter 2   Literature Review             
                Chapter 3   Methodology                   
                Chapter 4   Results                       
                Chapter 5   Discussion and Analysis       
                Chapter 6   Conclusions and Future Work   
                Chapter 7   Refection                     
                                                          
  End matter                References                    
                            Appendices (Optional)         
                            Index (Optional)              
  ------------- ----------- ----------------------------- --

  : Undergraduate report template structure
:::

### Example of a software/Web development main text structure {#subsec:se_chpters}

Notice that the "methodology" Chapter of Software/Web development in
Table [3.2](#tab:soft_eng_temp){reference-type="ref"
reference="tab:soft_eng_temp"} takes a standard software engineering
paradigm (approach). Alternatively, these suggested sections can be the
chapters of their own. Also, notice that "Chapter 5" in
Table [3.2](#tab:soft_eng_temp){reference-type="ref"
reference="tab:soft_eng_temp"} is "Testing and Validation" which is
different from the general report template mentioned in
Table [3.1](#tab:gen_template){reference-type="ref"
reference="tab:gen_template"}. Check with your supervisor if in doubt.

::: {#tab:soft_eng_temp}
  ----------- ----------------------------- -----------------------------
  Chapter 1   Introduction                  
  Chapter 2   Literature Review             
  Chapter 3   Methodology                   
                                            Requirements specifications
                                            Analysis
                                            Design
                                            Implementations
  Chapter 4   Testing and Validation        
  Chapter 5   Results and Discussion        
  Chapter 6   Conclusions and Future Work   
  Chapter 7   Reflection                    
  ----------- ----------------------------- -----------------------------

  : Example of a software engineering-type report structure
:::

### Example of an algorithm analysis main text structure

Some project might involve the implementation of a state-of-the-art
algorithm and its performance analysis and comparison with other
algorithms. In that case, the suggestion in
Table [3.3](#tab:algo_temp){reference-type="ref"
reference="tab:algo_temp"} may suit you the best.

::: {#tab:algo_temp}
  ----------- ---------------------------- -------------------------
  Chapter 1   Introduction                 
  Chapter 2   Literature Review            
  Chapter 3   Methodology                  
                                           Algorithms descriptions
                                           Implementations
                                           Experiments design
  Chapter 4   Results                      
  Chapter 5   Discussion and Analysis      
  Chapter 6   Conclusion and Future Work   
  Chapter 7   Reflection                   
  ----------- ---------------------------- -------------------------

  : Example of an algorithm analysis type report structure
:::

### Example of an application type main text structure

If you are applying some algorithms/tools/technologies on some
problems/datasets/etc., you may use the methodology section prescribed
in Table [3.4](#tab:app_temp){reference-type="ref"
reference="tab:app_temp"}.

::: {#tab:app_temp}
  ----------- ---------------------------- -------------------------------------------------
  Chapter 1   Introduction                 
  Chapter 2   Literature Review            
  Chapter 3   Methodology                  
                                           Problems (tasks) descriptions
                                           Algorithms/tools/technologies/etc. descriptions
                                           Implementations
                                           Experiments design and setup
  Chapter 4   Results                      
  Chapter 5   Discussion and Analysis      
  Chapter 6   Conclusion and Future Work   
  Chapter 7   Reflection                   
  ----------- ---------------------------- -------------------------------------------------

  : Example of an application type report structure
:::

### Example of a science lab-type main text structure

If you are doing a science lab experiment type of project, you may use
the methodology section suggested in
Table [3.5](#tab:lab_temp){reference-type="ref"
reference="tab:lab_temp"}. In this kind of project, you may refer to the
"Methodology" section as "Materials and Methods."

::: {#tab:lab_temp}
  ----------- ---------------------------- ------------------------------
  Chapter 1   Introduction                 
  Chapter 2   Literature Review            
  Chapter 3   Materials and Methods        
                                           Problems (tasks) description
                                           Materials
                                           Procedures
                                           Implementations
                                           Experiment set-up
  Chapter 4   Results                      
  Chapter 5   Discussion and Analysis      
  Chapter 6   Conclusion and Future Work   
  Chapter 7   Reflection                   
  ----------- ---------------------------- ------------------------------

  : Example of a science lab experiment-type report structure
:::

## Example of an Equation in LaTeX

Eq. [\[eq:eq_example\]](#eq:eq_example){reference-type="ref"
reference="eq:eq_example"} \[note that this is an example of an
equation's in-text citation\] is an example of an equation in LaTeX. In
Eq. [\[eq:eq_example\]](#eq:eq_example){reference-type="eqref"
reference="eq:eq_example"}, $s$ is the mean of elements
$x_i \in \mathbf{x}$:

$$\label{eq:eq_example} % label used to refer the eq in text
s = \frac{1}{N} \sum_{i = 1}^{N} x_i.$$

Have you noticed that all the variables of the equation are defined
using the **in-text** maths command \$.\$, and
Eq. [\[eq:eq_example\]](#eq:eq_example){reference-type="eqref"
reference="eq:eq_example"} is treated as a part of the sentence with
proper punctuation? Always treat an equation or expression as a part of
the sentence.

## Example of a Figure in LaTeX

Figure [3.1](#fig:chart_a){reference-type="ref" reference="fig:chart_a"}
is an example of a figure in LaTeX. For more details, check the link:

[wikibooks.org/wiki/LaTeX/Floats,\_Figures_and_Captions](https://en.wikibooks.org/wiki/LaTeX/Floats,_Figures_and_Captions).

Keep your artwork (graphics, figures, illustrations) clean and readable.
At least 300dpi is a good resolution of a PNG format artwork. However,
an SVG format artwork saved as a PDF will produce the best quality
graphics. There are numerous tools out there that can produce vector
graphics and let you save that as an SVG file and/or as a PDF file. One
example of such a tool is the "Flow algorithm software". Here is the
link for that: [flowgorithm.org](http://www.flowgorithm.org/download/).

<figure id="fig:chart_a">

<figcaption>Example figure in LaTeX.</figcaption>
</figure>

## Example of an algorithm in LaTeX

Algorithm [\[algo:algo_example\]](#algo:algo_example){reference-type="ref"
reference="algo:algo_example"} is a good example of an algorithm in
LaTeX.

::: algorithm
::: algorithmic
check if a number is even?
:::
:::

## Example of code snippet in LaTeX

Code
Listing [\[list:python_code_ex\]](#list:python_code_ex){reference-type="ref"
reference="list:python_code_ex"} is a good example of including a code
snippet in a report. While using code snippets, take care of the
following:

-   do not paste your entire code (implementation) or everything you
    have coded. Add code snippets only.

-   The algorithm shown in
    Algorithm [\[algo:algo_example\]](#algo:algo_example){reference-type="ref"
    reference="algo:algo_example"} is usually preferred over code
    snippets in a technical/scientific report.

-   Make sure the entire code snippet or algorithm stays on a single
    page and does not overflow to another page(s).

Here are three examples of code snippets for three different languages
(Python, Java, and CPP) illustrated in
Listings [\[list:python_code_ex\]](#list:python_code_ex){reference-type="ref"
reference="list:python_code_ex"},
[\[list:java_code_ex\]](#list:java_code_ex){reference-type="ref"
reference="list:java_code_ex"}, and
[\[list:cpp_code_ex\]](#list:cpp_code_ex){reference-type="ref"
reference="list:cpp_code_ex"} respectively.

``` {#list:python_code_ex .python language="Python" caption="Code snippet in \\LaTeX ~and  this is a Python code example" label="list:python_code_ex"}
import numpy as np

x  = [0, 1, 2, 3, 4, 5] # assign values to an array
evenSum = evenSummation(x) # call a function

def evenSummation(x):
    evenSum = 0
    n = len(x)
    for i in range(n):
        if np.mod(x[i],2) == 0: # check if a number is even?
            evenSum = evenSum + x[i]
    return evenSum
```

Here we used the "\\clearpage" command and forced-out the second listing
example onto the next page.

``` {#list:java_code_ex .java language="Java" caption="Code snippet in \\LaTeX ~and  this is a Java code example" label="list:java_code_ex"}
public class EvenSum{ 
    public static int evenSummation(int[] x){
        int evenSum = 0;
        int n = x.length;
        for(int i = 0; i < n; i++){
            if(x[i]%2 == 0){ // check if a number is even?
                evenSum = evenSum + x[i];
            }
        }
        return evenSum;     
    }
    public static void main(String[] args){ 
        int[] x  = {0, 1, 2, 3, 4, 5}; // assign values to an array
        int evenSum = evenSummation(x);
        System.out.println(evenSum);
    } 
} 
```

``` {#list:cpp_code_ex .objectivec language="C" caption="Code snippet in \\LaTeX ~and  this is a C/C++ code example" label="list:cpp_code_ex"}
int evenSummation(int x[]){
    int evenSum = 0;
    int n = sizeof(x);
    for(int i = 0; i < n; i++){
        if(x[i]%2 == 0){ // check if a number is even?
            evenSum = evenSum + x[i];
    	}
    }
    return evenSum;     
}

int main(){
    int x[]  = {0, 1, 2, 3, 4, 5}; // assign values to an array
    int evenSum = evenSummation(x);
    cout<<evenSum;
    return 0;
}
```

## Example of in-text citation style

### Example of the equations and illustrations placement and reference in the text

Make sure whenever you refer to the equations, tables, figures,
algorithms, and listings for the first time, they also appear (placed)
somewhere on the same page or in the following page(s). Always make sure
to refer to the equations, tables and figures used in the report. Do not
leave them without an **in-text citation**. You can refer to equations,
tables and figures more them once.

### Example of the equations and illustrations style

Write **Eq.** with an uppercase "Eq" for an equation before using an
equation number with (\\eqref{.}). Use "Table" to refer to a table,
"Figure" to refer to a figure, "Algorithm" to refer to an algorithm and
"Listing" to refer to listings (code snippets). Note that, we do not use
the articles "a," "an," and "the" before the words Eq., Figure, Table,
and Listing, but you may use an article for referring the words figure,
table, etc. in general.

For example, the sentence "A report structure is shown in **the**
Table [3.1](#tab:gen_template){reference-type="ref"
reference="tab:gen_template"}" should be written as "A report structure
is shown **in** Table [3.1](#tab:gen_template){reference-type="ref"
reference="tab:gen_template"}."

## Summary

Write a summary of this chapter.

 \
**Note:** In the case of **software engineering** project a Chapter
"**Testing and Validation**" should precede the "Results" chapter. See
Section [3.1.1](#subsec:se_chpters){reference-type="ref"
reference="subsec:se_chpters"} for report organization of such project.

# Results {#ch:results}

The results chapter tells a reader about your findings based on the
methodology you have used to solve the investigated problem. For
example:

-   If your project aims to develop a software/web application, the
    results may be the developed software/system/performance of the
    system, etc., obtained using a relevant methodological approach in
    software engineering.

-   If your project aims to implement an algorithm for its analysis, the
    results may be the performance of the algorithm obtained using a
    relevant experiment design.

-   If your project aims to solve some problems/research questions over
    a collected dataset, the results may be the findings obtained using
    the applied tools/algorithms/etc.

Arrange your results and findings in a logical sequence.

## A section

\...

## Example of a Table in LaTeX

Table [4.1](#tab:_ex_tab){reference-type="ref" reference="tab:_ex_tab"}
is an example of a table created using the package LaTeX"booktabs." do
check the link:
[wikibooks.org/wiki/LaTeX/Tables](https://en.wikibooks.org/wiki/LaTeX/Tables)
for more details. A table should be clean and readable. Unnecessary
horizontal lines and vertical lines in tables make them unreadable and
messy. The example in Table [4.1](#tab:_ex_tab){reference-type="ref"
reference="tab:_ex_tab"} uses a minimum number of liens (only necessary
ones). Make sure that the top rule and bottom rule (top and bottom
horizontal lines) of a table are present.

::: {#tab:_ex_tab}
  Bike               
  ---------- ------- -----------
  1-2 Type   Color     Price (£)
  Electric   black           700
  Hybrid     blue            500
  Road       blue            300
  Mountain   red             300
  Folding    black           500

  : Example of a table in LaTeX
:::

## Example of captions style

-   The **caption of a Figure (artwork) goes below** the artwork
    (Figure/Graphics/illustration). See example artwork in
    Figure [3.1](#fig:chart_a){reference-type="ref"
    reference="fig:chart_a"}.

-   The **caption of a Table goes above** the table. See the example in
    Table [4.1](#tab:_ex_tab){reference-type="ref"
    reference="tab:_ex_tab"}.

-   The **caption of an Algorithm goes above** the algorithm. See the
    example in
    Algorithm [\[algo:algo_example\]](#algo:algo_example){reference-type="ref"
    reference="algo:algo_example"}.

-   The **caption of a Listing goes below** the Listing (Code snippet).
    See example listing in
    Listing [\[list:python_code_ex\]](#list:python_code_ex){reference-type="ref"
    reference="list:python_code_ex"}.

## Summary

Write a summary of this chapter.

# Discussion and Analysis {#ch:evaluation}

Depending on the type of project you are doing, this chapter can be
merged with "Results" Chapter as " Results and Discussion" as suggested
by your supervisor.

In the case of software development and the standalone applications,
describe the significance of the obtained results/performance of the
system.

## A section

Discussion and analysis chapter evaluates and analyses the results. It
interprets the obtained results.

## Significance of the findings

In this chapter, you should also try to discuss the significance of the
results and key findings, in order to enhance the reader's understanding
of the investigated problem

## Limitations

Discuss the key limitations and potential implications or improvements
of the findings.

## Summary

Write a summary of this chapter.

# Conclusions and Future Work {#ch:con}

## Conclusions

Typically a conclusions chapter first summarizes the investigated
problem and its aims and objectives. It summaries the
critical/significant/major findings/results about the aims and
objectives that have been obtained by applying the key
methods/implementations/experiment set-ups. A conclusions chapter draws
a picture/outline of your project's central and the most signification
contributions and achievements.

A good conclusions summary could be approximately 300--500 words long,
but this is just a recommendation.

A conclusions chapter followed by an abstract is the last things you
write in your project report.

## Future work

This section should refer to
Chapter [4](#ch:results){reference-type="ref" reference="ch:results"}
where the author has reflected their criticality about their own
solution. The future work is then sensibly proposed in this section.

**Guidance on writing future work:** While working on a project, you
gain experience and learn the potential of your project and its future
works. Discuss the future work of the project in technical terms. This
has to be based on what has not been yet achieved in comparison to what
you had initially planned and what you have learned from the project.
Describe to a reader what future work(s) can be started from the things
you have completed. This includes identifying what has not been achieved
and what could be achieved.

A good future work summary could be approximately 300--500 words long,
but this is just a recommendation.

# Reflection {#ch:reflection}

Write a short paragraph on the substantial learning experience. This can
include your decision-making approach in problem-solving.

**Some hints:** You obviously learned how to use different programming
languages, write reports in LaTeXand use other technical tools. In this
section, we are more interested in what you thought about the
experience. Take some time to think and reflect on your individual
project as an experience, rather than just a list of technical skills
and knowledge. You may describe things you have learned from the
research approach and strategy, the process of identifying and solving a
problem, the process research inquiry, and the understanding of the
impact of the project on your learning experience and future work.

Also think in terms of:

-   what knowledge and skills you have developed

-   what challenges you faced, but was not able to overcome

-   what you could do this project differently if the same or similar
    problem would come

-   rationalize the divisions from your initial planed aims and
    objectives.

A good reflective summary could be approximately 300--500 words long,
but this is just a recommendation.

 \
**Note:** The next chapter is "**References**," which will be
automatically generated if you are using BibTeX referencing method. This
template uses BibTeX referencing. Also, note that there is difference
between "References" and "Bibliography." The list of "References"
strictly only contain the list of articles, paper, and content you have
cited (i.e., refereed) in the report. Whereas Bibliography is a list
that contains the list of articles, paper, and content you have cited in
the report plus the list of articles, paper, and content you have read
in order to gain knowledge from. We recommend to use only the list of
"References."

::: appendices
# An Appendix Chapter (Optional) {#appn:A}

Some lengthy tables, codes, raw data, length proofs, etc. which are
**very important but not essential part** of the project report goes
into an Appendix. An appendix is something a reader would consult if
he/she needs extra information and a more comprehensive understating of
the report. Also, note that you should use one appendix for one idea.

An appendix is optional. If you feel you do not need to include an
appendix in your report, avoid including it. Sometime including
irrelevant and unnecessary materials in the Appendices may unreasonably
increase the total number of pages in your report and distract the
reader.

# An Appendix Chapter (Optional) {#appn:B}

\...
:::

[^1]: Example footnote: footnotes are useful for adding external sources
    such as links as well as extra information on a topic or word or
    sentence. Use command \\footnote{\...} next to a word to generate a
    footnote in LaTeX.

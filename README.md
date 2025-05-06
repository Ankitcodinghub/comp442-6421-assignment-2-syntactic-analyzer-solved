# comp442-6421-assignment-2-syntactic-analyzer-solved
**TO GET THIS SOLUTION VISIT:** [COMP442_6421 Assignment 2-Syntactic Analyzer Solved](https://www.ankitcodinghub.com/product/comp442_6421-assignment-2-syntactic-analyzer-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;96194&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP442_6421 Assignment 2-Syntactic Analyzer Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
This assignment is about the design and implementation of a syntactic analyzer for the language specified by the grammar given below. The syntactic analyzer should use as input the token stream produced by the lexical analyzer that you have produced in assignment #1, and prove whether or not the token stream is a valid program according to the grammar given below. While doing so, it should locate, report, and recover from eventual syntax errors. It should also write to a file a trace of the derivation that is proving that the input token stream can be derived from the starting symbol of the grammar.

The assignment includes two grading source files. These files should be used as-is and not be altered in any way. Completeness of testing is a major grading topic. You are responsible for providing appropriate test cases that test for a wide variety of valid and invalid cases in addition to what is in the grading source files provided.

Grammar

G= (N,T,S,R)

N – Nonterminal Symbols

<pre>START, aParams, aParamsTail, addOp, arithExpr, arraySize, assignOp, assignStat, classDecl,
expr, fParams, fParamsTail, factor, funcBody, funcDecl, funcDef, funcHead, functionCall,
idnest, implDef, indice, memberDecl, multOp, prog, relExpr, returnType, sign, statBlock,
statement, structOrImplOrFunc, term, type, varDecl, varDeclOrStat, variable, visibility
</pre>
T – Terminal Symbols

,, +, -, |, [, intLit, ], =, struct, id, {, }, ;, (, ), floatLit, !, :, void, ., *, /, &amp;, inherits, eq, geq, gt, leq, lt, neq, if, then, else, read, return, while, write, float, integer, private, public, func, impl, let

S – Starting Symbol

START

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
R – Rules

&lt;START&gt;

&lt;prog&gt; &lt;structOrImplOrFunc&gt; &lt;structDecl&gt; &lt;implDef&gt;

&lt;funcDef&gt; &lt;visibility&gt; &lt;memberDecl&gt; &lt;funcDecl&gt; &lt;funcHead&gt; &lt;funcBody&gt; &lt;varDeclOrStat&gt; &lt;varDecl&gt; &lt;statement&gt;

&lt;assignStat&gt; &lt;statBlock&gt; &lt;expr&gt; &lt;relExpr&gt; &lt;arithExpr&gt; &lt;sign&gt; &lt;term&gt; &lt;factor&gt;

&lt;variable&gt; &lt;functionCall&gt; &lt;idnest&gt;

&lt;indice&gt; &lt;arraySize&gt; &lt;type&gt; &lt;returnType&gt; &lt;fParams&gt; &lt;aParams&gt; &lt;fParamsTail&gt; &lt;aParamsTail&gt; &lt;assignOp&gt; &lt;relOp&gt; &lt;addOp&gt; &lt;multOp&gt;

Notes

</div>
<div class="column">
::= &lt;prog&gt;

::= {{&lt;structOrImplOrfunc&gt;}}

::= &lt;structDecl&gt; | &lt;implDef&gt; | &lt;funcDef&gt;

::= ‘struct’ ‘id’ [[‘inherits’ ‘id’ {{‘,’ ‘id’}}]] ‘{‘ {{&lt;visibility&gt; &lt;memberDecl&gt;}} ‘}’ ‘;’ ::= ‘impl’ ‘id’ ‘{‘ {{&lt;funcDef&gt;}} ‘}’

::= &lt;funcHead&gt; &lt;funcBody&gt;

::= ‘public’ | ‘private’

::= &lt;funcDecl&gt; | &lt;varDecl&gt;

::= &lt;funcHead&gt; ‘;’

::= ‘func’ ‘id’ ‘(‘ &lt;fParams&gt; ‘)’ ‘-&gt;’ &lt;returnType&gt;

::= ‘{‘ {{&lt;varDeclOrStat&gt;}} ‘}’

::= &lt;varDecl&gt; | &lt;statement&gt;

::= ‘let’ ‘id’ ‘:’ &lt;type&gt; {{&lt;arraySize&gt;}} ‘;’

::= &lt;assignStat&gt; ‘;’

| ‘if’ ‘(‘ &lt;relExpr&gt; ‘)’ ‘then’ &lt;statBlock&gt; ‘else’ &lt;statBlock&gt; ‘;’ | ‘while’ ‘(‘ &lt;relExpr&gt; ‘)’ &lt;statBlock&gt; ‘;’

| ‘read’ ‘(‘ &lt;variable&gt; ‘)’ ‘;’

| ‘write’ ‘(‘ &lt;expr&gt; ‘)’ ‘;’

| ‘return’ ‘(‘ &lt;expr&gt; ‘)’ ‘;’

| &lt;functionCall&gt; ‘;’

::= &lt;variable&gt; &lt;assignOp&gt; &lt;expr&gt;

::= ‘{‘ {{&lt;statement&gt;}} ‘}’ | &lt;statement&gt; | EPSILON ::= &lt;arithExpr&gt; | &lt;relExpr&gt;

::= &lt;arithExpr&gt; &lt;relOp&gt; &lt;arithExpr&gt;

::= &lt;arithExpr&gt; &lt;addOp&gt; &lt;term&gt; | &lt;term&gt;

::= ‘+’ | ‘-‘

::= &lt;term&gt; &lt;multOp&gt; &lt;factor&gt; | &lt;factor&gt;

::= &lt;variable&gt;

| &lt;functionCall&gt;

| ‘intLit’ | ‘floatLit’ | ‘(‘ &lt;arithExpr&gt; ‘)’

| ‘not’ &lt;factor&gt;

| &lt;sign&gt; &lt;factor&gt;

::= {{&lt;idnest&gt;}} ‘id’ {{&lt;indice&gt;}}

::= {{&lt;idnest&gt;}} ‘id’ ‘(‘ &lt;aParams&gt; ‘)’ ::= ‘id’ {{&lt;indice&gt;}} ‘.’

| ‘id’ ‘(‘ &lt;aParams&gt; ‘)’ ‘.’ ::= ‘[‘ &lt;arithExpr&gt; ‘]’

::= ‘[‘ ‘intNum’ ‘]’ | ‘[‘ ‘]’ ::= ‘integer’ | ‘float’ | ‘id’ ::= &lt;type&gt; | ‘void’

::= ‘id’ ‘:’ &lt;type&gt; {{&lt;arraySize&gt;}} {{&lt;fParamsTail&gt;}} | EPSILON ::= &lt;expr&gt; {{&lt;aParamsTail&gt;}} | EPSILON

::= ‘,’ ‘id’ ‘:’ &lt;type&gt; {{&lt;arraySize&gt;}}

::= ‘,’ &lt;expr&gt;

::= ‘=’

::= ‘eq’ | ‘neq’ | ‘lt’ | ‘gt’ | ‘leq’ | ‘geq’ ::= ‘+’ | ‘-‘ | ‘or’

::= ‘*’ | ‘/’ | ‘and’

</div>
</div>
<div class="layoutArea">
<div class="column">
<ul>
<li>Terminals (lexical elements, or tokens) are represented in single quotes ‘likeThis’.</li>
<li>Non-terminals are represented between angle brackets &lt;likeThis&gt;.</li>
<li>The empty phrase is represented by EPSILON.</li>
<li>EBNF-style repetition notation is represented using double curly brackets {{like this}}. It represents zero or
more occurrence of the sentential form enclosed in the brackets.
</li>
<li>EBNF-style optionality notation is represented using double square brackets [[like this]]. It represents zero or
one occurrence of the sentential form enclosed in the brackets.
</li>
<li>id follows the specification for program identifiers found in assignment #1.</li>
<li>intLit, floatLit, follow specification for integer and float literals found in assignment #1</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Work to submit

Document

You must provide a short document that includes the following sections:

</div>
</div>
<div class="layoutArea">
<div class="column">
Section 1.

Section 2. Section 3. Section 4.

</div>
<div class="column">
Transformed grammar into LL(1) : Remove all the EBNF notations and replace them by right-recursive list-generating productions. Analyze the syntactical definition (using tools) and list in your documentation all the ambiguities and left recursions. Modify the grammar so that the left recursions and ambiguities are removed without modifying the language. Include in your documentation the set of productions that can be parsed using the top-down predictive parsing method, i.e. an LL(1) grammar.

FIRST and FOLLOW sets : Derive the FIRST and FOLLOW sets for each non-terminal in your transformed grammar.

Design : Give a brief overview of the overall structure of your solution, as well as a brief description of the role of each component of your implementation.

Use of tools : Identify all the tools/libraries/techniques that you have used in your analysis or implementation and justify why you have used these particular ones as opposed to others.

</div>
</div>
<div class="layoutArea">
<div class="column">
Implementation

• Parser : Implement a predictive parser (recursive descent or table-driven) for your modified set of grammar rules.

<ul>
<li>The result of the parser should be the creation of a tree data structure representing the parse tree as identified by
the parsing process. This tree will become the intermediate representation used by the two following assignments. When parsing a file named, for example, originalfilename, the parser should write into a file named originalfilename.outderivation the derivation that corresponds to the original program. When syntax errors are found, error messages should be output in a file named originalfilename.outsyntaxerrors.
</li>
<li>Derivationoutput:Yourparsershouldwritetoafiletheleftmostderivationthatprovesthatthesourceprogramcan be derived from the starting symbol. For an example of a derivation, see slide set 3, slide 17.</li>
<li>Error reporting : The parser should properly identify all the errors in the input program and print a meaningful message to the user for each error encountered. The error messages should be informative on the nature of the errors, as well as the location of the errors in the input file.</li>
<li>Error recovery : The parser should implement an error recovery method that permits to report all errors present in the source code.</li>
<li>Test cases : Write a set of source files that enable to test the parser for all syntactical structures involved in the language. Include cases testing for a variety of different errors to demonstrate the accuracy of your error reporting and recovery.</li>
<li>Driver: Include a driver that parses all your test files. For each test file, the corresponding outsyntaxerrors, and outderivation files should be generated.</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
Assignment submission requirements and procedure

<ul>
<li>Each submitted assignment should contain four components: (1) the source code, (2) a group of test files, (3) a brief report, and (4) an executable named parserdriver, that extracts the tokens from all your test files. For each test file, the corresponding outsyntaxerrors and outderivation files should be generated.</li>
<li>The assignment statement provides test files (.src) and their corresponding output files.</li>
<li>The source code should be separated into modules using a comprehensible coding style.</li>
<li>The assignment should be submitted through moodle in a file named: “A#_student-id” (e.g. A1_1234567, for
Assignment #1, student ID 1234567) and the report must in a PDF format.
</li>
<li>You may use any language you want in the project and assignments but the only fully supported language during
the lab is Java.
</li>
<li>You have to submit your assignment before midnight on the due date on moodle.</li>
<li>The file submitted must be a .zip file
The marking will be done in a short presentation to the marker. A schedule will be provided to you by email in the days before the due date. You will be given a short time for the presentation, so make sure that you are ready to effectively demonstrate all the elements mentioned in the “Work to submit” section above.
</li>
</ul>
</div>
</div>
</div>

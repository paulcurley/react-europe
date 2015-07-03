
#Improving Your Workflow With Code Transformation

Most React developers already use a build pipeline to transform their JSX into vanilla JavaScript. This is usually under-utilised only doing basic transformations such as concatenation, minification and linting. In this talk, Sebastian will go over how this already existing infrastructure can be further utilised to perform even more significant code transformations such as transpilation, optimisation, profiling and more, reducing bugs, making your code faster and you as a developer more productive and happy.

##Sebastian McKenzie 

@sebmck

AST - Abstrast syntax tree
parser > transformer > generator

parser
    lexical analiysis
        read tokens

    syntactic analysis
        dealing wiht tokens
        

traversal
    static analysis


generator
turns tree back to code that was infered from traversal

optmise
    inline elements - 
    

future
    dead code elemination/minification - intergrate with flow?
    constant folding/stati cevaluation - will slow down compilation, but speed up end
    static analisys/linting - type checking, etcg

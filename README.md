# A Self Interpreting Spartan

Implement a minimal type theory and use it to build a self interpreter. Try to embed terms in JSON objects with javascript closure metatheory.

Bonuses, express Univalence compile, prove correctness, compile to typed web-assembly.

## Rwrr

We will implement Rwrr a javascript rewriting interpreter. The API is minimal.

```
match(expression, rule) 
rewrite(expression, rule)
evaluate(expression, environment)
```

It is inspired by mathematica and TRS presented in literature such as Term Rewriting Systems and Advanced Topics in Term Rewriting.

Rwrrr implements a rewriting logic and type checking ideas can be ported through this logic.

## Parser

We will use simple tools to define a basic extensible parser implemented in Rwrr.

* Just write the parser https://tiarkrompf.github.io/notes/?/just-write-the-parser/aside1
* Post Modern Compiler Design https://www.cs.purdue.edu/homes/rompf/pmca/vol1/

## Spartan Type Theory

* https://github.com/andrejbauer/spartan-type-theory
* https://github.com/MaiaVictor/calculus-of-constructions

## Thoerem Proving

* Term rewriting and beyond — theorem proving in Isabelle

## Rewriting

* javascript term rewriting https://github.com/fbreuer/rewritr
* Algebra in my browser https://www.youtube.com/watch?v=S2OEPFbsl50

```
ReplaceAll [Object, [Rules]]
```

* lisp mathematica https://dl.acm.org/doi/abs/10.1145/1089419.1089421?download=true
* matematica evaluation https://reference.wolfram.com/language/tutorial/EvaluationOfExpressionsOverview.html

Expression

```
{Expression:{}}
```

Rewrite

```
replace({Expression1:{}}, {Expression1: {Expression2: {}}) == {Expression2:{}}
```

should implement what is needed for

* Simulation of Turing machines by a regular rewrite rule

theory

* Computing with Rewrite Systems https://core.ac.uk/download/pdf/82345385.pdf

## JavaScript metatheory

* mechanized metatheory for the mases https://repository.upenn.edu/cgi/viewcontent.cgi?article=1248&context=cis_papers
* closure calculus? https://dl.acm.org/doi/10.1145/3294032.3294085
* binders and alpha for free?

## Self Interpreters in Lambda Calculus

* https://crypto.stanford.edu/~blynn/lambda/



# Advanced

## Univalance

* A self contained and brief formulation of https://arxiv.org/pdf/1803.02294.pdf

## Proof Carrying Code

* https://www.cs.princeton.edu/~appel/papers/pccmodel.pdf

## Weird

* Fully Automated HTML and Javascript Rewriting for Constructing a Self-healing Web Proxy https://arxiv.org/pdf/1803.08725.pdf

## Quantifier Elimination

* Computation-Oriented Reductions of Predicate to Propositional Logic

## Unification

## Compiling

* An Architecture for Analysis https://sites.cs.ucsb.edu/~jmcmahan/research/top_picks_18.pdf

## Redex

* https://github.com/racket/redex

# Weight Space Programming

Weight-space programming papers, code and runnable examples for representing and constructing programs in neural-network weights.

[Explore the guide](https://weightspaceprogramming.tech/) · [Search the research library](https://weightspaceprogramming.tech/research/) · [Reading list and citation exports](https://github.com/weightspaceprogramming/reading-list)

- [Learn the concepts](https://weightspaceprogramming.tech/learn/how-neural-networks-represent-programs/) and [compare construction methods](https://weightspaceprogramming.tech/learn/comparing-methods/).
- [Follow the history](https://weightspaceprogramming.tech/history/) through original sources.
- [Build a reusable neural function](https://weightspaceprogramming.tech/build/reusable-neural-function/) with [Program-as-Weights](https://programasweights.com/), or [open its playground](https://programasweights.com/playground).
- [Find code and implementations](https://weightspaceprogramming.tech/build/code-and-implementations/): runnable examples, original experiment repositories and model downloads.
- [Read the experiments and critiques](https://weightspaceprogramming.tech/analysis/).

## Code and runnable examples

- [Program-as-Weights (NeurIPS 2026)](https://weightspaceprogramming.tech/research/program-as-weights/) introduces a programming paradigm for fuzzy functions, a compiler–interpreter interface and the FuzzyBench benchmark. PAW specifically trains a compiler to turn natural-language function specifications into LoRA adapters that edit a frozen interpreter’s weights. [Run its urgency and routing examples](https://github.com/weightspaceprogramming/examples#2-compile-and-reuse-an-email-urgency-function-with-paw).
- [PAW and prompting outputs](https://github.com/weightspaceprogramming/examples#email-triage-and-request-routing): compare the same Qwen3-0.6B model with a compiled adapter and a prompted specification.
- [Sparks weight-reading heatmaps](https://github.com/weightspaceprogramming/examples/blob/main/WEIGHT_READING.md): inspect four released game networks and reproduce the input-layer norm calculation discussed by Sean Goedecke.
- [Tracr token counter](https://github.com/weightspaceprogramming/examples#1-compile-a-token-counter-with-tracr): compile RASP into transformer weights and check exact counts on CPU.

Edited by [Yuntian Deng](https://yuntiandeng.com/), a coauthor of Program-as-Weights.

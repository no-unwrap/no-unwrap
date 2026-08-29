Computer vision researcher and aspiring cert-grade systems engineer.

My research is in visual saliency and attention, with a focus on how
perception differs across populations that datasets tend to leave out.
Alongside it I work on safety-critical software: systems built to be
verified rather than merely tested.

Learned components are steadily entering safety-critical systems, and the
two halves of that problem are usually held by different people. I want to
be an engineer who can be trusted with both.

Mostly heads-down; occasional contributions to projects I depend on or admire.

## Philosophy

Some of these I work in, some I'm learning my way into. All of them shape how
I think about building software.

<table width="100%">
<colgroup>
<col width="20%">
<col width="42%">
<col width="38%">
</colgroup>
<thead>
<tr><th></th><th>Modern</th><th>Foundational</th></tr>
</thead>
<tbody>
<tr><td><b>Systems</b></td><td>Rust, Zig</td><td>C, C++</td></tr>
<tr><td><b>Functional</b></td><td>Haskell, Lean 4</td><td>Lisp, Scheme</td></tr>
<tr><td><b>Research</b></td><td>Python, Swift</td><td>LaTeX</td></tr>
</tbody>
</table>

In systems, I'm drawn to ownership, type-level invariants, allocator
discipline, and compile-time composition. *The closer to the metal the
work runs, the more interesting it gets.*

In functional programming, I'm drawn to effect tracking, algebraic data
types, totality checking, and the bias toward total functions over partial
ones. *The right type makes the wrong state hard to spell.*

## Discipline

<table width="100%">
<colgroup>
<col width="35%">
<col width="65%">
</colgroup>
<tr><td><b>No swallowed failures</b></td><td>Errors propagate or get explicit rationale</td></tr>
<tr><td><b>Illegal states unrepresentable</b></td><td>Encode invariants at the type level</td></tr>
<tr><td><b>Pure cores, effectful edges</b></td><td>Effects tracked; total where the type permits</td></tr>
<tr><td><b>Exhaustive pattern matching</b></td><td>No catch-alls that swallow new cases</td></tr>
<tr><td><b>No accidental quadratics</b></td><td>Complexity claimed up front; WCET when deployed</td></tr>
<tr><td><b>Strict-by-default static analysis</b></td><td>Explicit allowance ledger for every exception</td></tr>
<tr><td><b>Qualified toolchains, MISRA-grade source</b></td><td>Where the deployment context calls for it</td></tr>
<tr><td><b>Mutation-tested coverage</b></td><td>Tests that don't kill mutations get rewritten</td></tr>
<tr><td><b>Supply-chain discipline</b></td><td><code>cargo-deny</code> for Rust; equivalents elsewhere</td></tr>
<tr><td><b>Independent peer review</b></td><td>Before any change ships</td></tr>
</table>

## Elsewhere

[no-unwrap.github.io](https://no-unwrap.github.io)

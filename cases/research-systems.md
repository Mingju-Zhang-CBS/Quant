# AI-Assisted Research Systems

**Method note / background.**

**Question:** How can more generated ideas lead to more reliable learning?

My recent experience includes research-specification workflows, factor implementation checks, lineage, experiment recovery and separating evaluation feedback. The original delivery remains private. This note explains general public research principles; the [new offline companion](https://github.com/Mingju-Zhang-CBS/agentic-quant-research) supplies independently written runnable evidence.

## Preserve distinctions

A generated proposal is not a valid implementation. A valid implementation is not a useful predictor. A predictor can add no incremental value to a fixed model. A model improvement can disappear once position sizing, constraints and costs are applied. A research proxy cannot by itself establish executable fills. Keeping these stages separate makes the next decision more specific.

Suppose six proposals produce three admissible expressions, one duplicate and two technical failures. The admitted count is three; it is not three successful alphas. If validation picks one and its confirmation result is negative, the correct outcome is a failed hypothesis with an intact experiment history. These are the actual categories shown in the new public workflow.

## Evidence and recovery

Record input and source identity, candidate versions, transformations, selection rules and a frozen cohort. Recovery should verify the identity of the work it is resuming. Errors should retain stage-specific explanations rather than being silently skipped. Evaluation-only outputs should not become material for later generation under a claim of untouched confirmation.

The public companion uses a static proposal fixture and a local operator whitelist. It calls no LLM and runs no company Qlib provider. This deliberately bounded implementation demonstrates the control flow while preserving the distinction between historical experience and newly measured results.

## Contribution boundary

[Microsoft RD-Agent](https://github.com/microsoft/RD-Agent), Qlib and other upstream tools retain their authorship. I describe extending research workflows rather than originating the whole upstream framework. The existing employer delivery's operational counts, memory, private prompts and evaluations are not public demo evidence. Its internal clean-room/delivery status does not establish permission to republish its code.

## Skills and limitations

The area demonstrates research orchestration, data contracts, diagnostics, dependency management, lineage and communication of uncertainty. A more complete agent comparison would need lawful data, independently frozen tasks, actual proposal-generation policies, compute budgets and fresh evaluation. Those are future empirical questions, not capabilities claimed from the offline fixture alone.

[Research directory](../README.md)

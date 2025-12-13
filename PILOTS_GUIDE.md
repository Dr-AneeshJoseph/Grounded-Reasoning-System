# GRS 12.0 Pilot's Manual

**Welcome, Pilot.**
You have installed the Grounded Reasoning System. This document explains how to "steer" the cognitive architecture. Unlike standard chat, GRS 12.0 listens for specific **Intent Signals**.

---

## 1. Reading the HUD (The Trace)

For complex queries, GRS displays the **Lucid Trace**. Here is how to read it:


[GRS_TRACE v12.0]
⟳ LOOP_0: Noise Filtered [Yes] | Vector: [Correction]  <-- System realized you are fixing a mistake.
⚙️ MODE: [CODE] (Reason: User requested Python script) <-- The active cognitive engine.
🛡️ SAFETY: [Pass]                                      <-- Safety Lock status.
🧠 REFLEXION: "Initially used O(n^2), but O(n) is possible..." <-- The system correcting itself.

 * If Noise Filtered = Yes: The system ignored your emotional tone to focus on the task.
 * If Vector = Divergence: The system flushed the previous context to start fresh.


2. Steering Commands
You can override the system's decisions using these natural language triggers:
Force a Mode
If the system is being too analytical, force it into Story mode.
> You: "Reroute to [STORY]. Explain this like a fable."
> 
If the system is being too vague, force it into Logic mode.
> You: "Reroute to [LOGIC]. Use the 5-Layer Framework."
> 
Deepen the Analysis
If the answer is too shallow, trigger a "Deep Think" cycle.
> You: "Expand. Show the Tree of Thoughts branches you considered."
> 
Correct the Behavior (Antifragility)
GRS learns from corrections. Be explicit.
> You: "Wrong. Never use bullet points for code explanations."
> System Action: Updates [SESSION_HEURISTICS] to ban bullet points for code.
> 



3. Troubleshooting
The System Refuses to Answer
 * Cause: You likely triggered the Safety Lock or the Falsifiability Constraint.
 * Fix: Check if your query asks for dangerous instructions or unverifiable metaphysical claims. Refine the query to be empirical.
The System "Stops & Asks"
 * Cause: Your intent was ambiguous (e.g., "Fix it").
 * Fix: Provide the missing context (e.g., "Fix the indentation error in the Python script").
Remember: You are not chatting with a chatbot. You are operating a reasoning engine. Drive it.



## 4. System Maintenance (Contextual Decay)

In very long sessions, the system may "forget" it is GRS 12.0.

**The Integrity Check:**
Periodically ask: *"Status Report."*

**The Response Should Be:**
> `>> GRS 12.0 ACTIVE. [ANTIFRAGILE STATE]: { ... }`

**If the response is generic:**
The Promptware has decayed. **Action:** Paste the `promptware.md` code block again to "Hot Reload" the kernel.

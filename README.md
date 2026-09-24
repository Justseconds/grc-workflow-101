<div align="center">

# Justseconds

### *Where we break it down, build you up, and help you stand out.*

</div>

---

## 🌅 GRC Workflow 101

> **GRC isn't just checking boxes. It's proving what's true.**

This repository is my portfolio project. I built it to learn Governance, Risk, and Compliance (GRC) by making a practical assessment tool from scratch.

It includes two **free, blank Excel workbooks** that take you through an assessment step by step, from defining what you're reviewing to documenting the final decision.

I'm sharing it as a standalone example of how I think through a GRC assessment. I hope it also helps other beginners see how the pieces connect.

> [!IMPORTANT]
> Both workbooks are **blank portfolio templates**. They contain no real findings, systems, evidence, or company data. Nothing here represents a completed audit, a passed assessment, or a certification.

---

## 💡 Why I built this

When I started learning GRC, I kept running into terms like *risk register*, *gap analysis*, *POAM*, and *evidence*. Each one made sense on its own, but I couldn't see how they fit together in real work.

So I built the workflow myself. I wanted one place where every item could be traced from start to finish:

**What did we review? → What's the evidence? → What's the risk? → Who owns the fix? → What did we decide?**

Building it taught me more than reading about it ever did. That's the Justseconds approach: break it down, then build it up.

---

## ⬇️ Download the workbooks

Both workbooks have the same nine tabs and the same workflow. The only difference is the look.

| | 🌅 Sunset Society version | ⚪ Neutral version |
|---|---|---|
| **File** | [Sunset-Society-GRC-Template.xlsx](Sunset-Society-GRC-Template.xlsx?raw=true) | [GRC Empty template.xlsx](GRC%20Empty%20template.xlsx?raw=true) |
| **Style** | Colorful and branded | Clean and unbranded |
| **Purpose** | A version I designed for Sunset Society, the company I work for | A version anyone can download and adapt |
| **Start Here tab** | Sunset Society workflow cover | Includes a numbered workbook map |
| **Contents** | Blank template | Blank template |

> [!TIP]
> Open the files in **Microsoft Excel** so the risk scoring works as intended. If a link opens a preview instead of downloading, use the **Download raw file** button on the file page.

---

## 🔁 The workflow in plain language

**Scope → Framework → Gaps → Risks → Remediation → Tests → Evidence → Decisions**

| Stage | In plain language |
|---|---|
| 🎯 **Scope** | *What are we looking at?* Name the system, the people, the data, and where the boundaries are. |
| 📚 **Framework** | *What should "good" look like?* Choose the requirements that apply, and write down why. |
| 🔍 **Gaps** | *Where do we fall short, or where are we unsure?* Compare what's in place to what's required. |
| ⚠️ **Risks** | *What could go wrong, and how bad would it be?* Rate each risk and give it an owner. |
| 🛠️ **Remediation** | *How will we fix it?* Assign each fix an owner, a priority, and a target date. |
| 🧪 **Tests** | *Does the control actually work?* Decide what counts as a pass *before* testing. |
| 📁 **Evidence** | *How do we know?* Record what was actually reviewed and where it's stored. |
| ✅ **Decisions** | *What did we decide, and who decided?* Document the outcome, any accepted risk, and follow-up. |

---

## 🗂️ The nine tabs

| # | Tab | What it's for |
|---|---|---|
| 1 | **Start Here** | Overview of the workflow, questions to ask before you begin, the assessment states, and the risk scoring scale |
| 2 | **Scope** | The assessment ID, system, business purpose, owners, boundaries, users, assets, data, and review date |
| 3 | **Framework Guide** | An introduction to 11 references and when each one might apply |
| 4 | **Gap Analysis** | Each requirement compared to the current state, with the evidence reviewed and an assessment state |
| 5 | **Risk Register** | Risks, likelihood × impact scores, owners, responses, and residual risk |
| 6 | **Actions POAM** | A Plan of Action and Milestones: one row per fix, with owners, dates, and retest results |
| 7 | **Control Tests** | Test steps, expected vs. observed results, tester, and date |
| 8 | **Evidence Log** | What was reviewed, its source, when, where it's kept privately, and any limitations |
| 9 | **Decision Log** | The decision requested, options considered, the decision made, who made it, and follow-up |

The tabs connect through shared IDs (Gap ID, Risk ID, Action ID, Evidence ID, and so on), so any item can be traced from scope to decision.

---

## 📊 Risk scoring

The Risk Register calculates a score once you enter both values:

> **Risk score = Likelihood (1–5) × Impact (1–5)**

| Rating | Score range |
|---|---|
| 🔴 Critical | 20–25 |
| 🟠 High | 15–19 |
| 🟡 Medium | 8–14 |
| 🟢 Low | 1–7 |

For example, a likelihood of **3** and an impact of **4** gives a score of **12**, which is **Medium**. The register also tracks *residual* risk, meaning the risk that remains after a fix is in place. Agree on the scale with the risk owner before you use it.

---

## 🎯 The five assessment states

Every requirement gets one honest state:

| State | What it means |
|---|---|
| 🔴 **Known gap** | We've confirmed the requirement is not met. |
| 🟠 **Unverified** | We don't have enough evidence yet to say either way. |
| 🟡 **Partial** | Part of the requirement is met, but not all of it. |
| 🟢 **Verified** | Evidence was reviewed and the control was confirmed. |
| ⚪ **Not applicable** | The requirement doesn't apply to this scope, and we've documented why. |

### Why missing evidence means "Unverified"

This was one of the biggest lessons for me: **"not in the document" does not mean the control failed.**

**Example:** A policy says multi-factor authentication (MFA) is required for admin accounts, but no screenshot, settings export, or access report has been provided.

- ❌ It's **not** a Known gap. Nobody has shown that MFA is off.
- ❌ It's **not** Verified. Nobody has shown that MFA is on.
- ✅ It's **Unverified** until someone investigates.

**Next step:** Request evidence from the system owner. Once it's reviewed, the state changes to **Verified**, **Partial**, or **Known gap**, based on what the evidence actually shows.

Being honest about what we *don't* know yet is part of proving what's true.

---

## 📚 The Framework Guide

The Framework Guide tab introduces **11 references**, including:

- **NIST CSF** (Cybersecurity Framework)
- **NIST SP 800-53**
- **ISO/IEC 27001**
- **SOC 2**
- **CMMC**

The guide also covers NIST RMF, NIST SP 800-171, CIS Controls, OWASP ASVS, the NIST Privacy Framework, and FedRAMP. For each one, it explains what kind of reference it is, what question it answers, when to consider it, and links to its official source.

> [!NOTE]
> The Framework Guide is **selection guidance only**. It helps you decide which requirements may apply and why. Listing or mapping to a framework does **not** prove compliance, certification, or authorization.

---

## 🚀 Practice with a fictional system

The best way to learn the workflow is to try it. Pick something fictional, like a small online bookstore with a customer signup form.

1. **Download** either workbook and open it in Excel.
2. **Read the Start Here tab** to get familiar with the flow and the five states.
3. **Fill in Scope.** Describe the system, what it does, who owns it, and what data it collects.
4. **Choose a framework** from the Framework Guide and write one sentence on why it applies.
5. **Add a few rows to Gap Analysis.** Anything you can't prove yet should be marked **Unverified**.
6. **Log a risk** in the Risk Register. Enter likelihood and impact, and watch the score calculate.
7. **Plan a fix** in Actions POAM with an owner and a target date.
8. **Write a test** in Control Tests. Set the expected result first, then record what you "observed."
9. **Log your evidence** in the Evidence Log. Fictional references are fine.
10. **Record a decision** in the Decision Log.

🎉 That's one complete trace, from scope to decision.

---

## 🌇 How I would use this at Sunset Society

Sunset Society is the company I work for, and I designed the colorful version with it in mind. Here's how I would apply this workflow when planning and reviewing technology projects:

- **Before a project starts,** I'd scope what it touches, including systems, vendors, users, and any personal data.
- **I'd choose requirements on purpose,** and document why each framework or reference applies to that project.
- **I'd treat unknowns as Unverified** instead of assuming something is secure or insecure.
- **I'd turn gaps into risks and actions** with clear owners and dates, so security is planned alongside the project, not after it.
- **I'd record decisions** so there's a clear history of what was accepted, fixed, or scheduled for follow-up.

> [!IMPORTANT]
> The workbooks published here are **blank portfolio templates**. They don't contain Sunset Society's systems, findings, or evidence, and they don't represent any completed assessment, audit, or certification.

---

## 🔒 Keep it safe

- ✅ Share only **blank** templates or **fictional** examples publicly.
- 🚫 Never put real findings, personal data, internal URLs, passwords, or system details in a public copy.
- 🔐 If you use this for real work, keep your filled-in copy in a **private**, access-controlled location.

---

## 💬 Feedback

I'm still learning, and I'd love to hear from you. If you have ideas for a better field, a clearer explanation, or a tab you'd add, please open an issue in this repository.

---

<div align="center">

**Justseconds**<br>
*Where we break it down, build you up, and help you stand out.*<br><br>
Built by Joshua Tubman as a GRC learning and portfolio project.

</div>

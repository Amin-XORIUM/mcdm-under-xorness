# Multiple Criteria Decision Making Under Xorness

Multiple Criteria Decision Making (MCDM) is concerned with making decisions in the
presence of multiple, conflicting criteria. In this project, we extend and develop
MCDM methods to address multi-criteria decision problems under **Xorness**.

📄 Based on the paper *Multiple Criteria Decision Making Under Xorness* (Amin Hocine).

---

## What is Xorness and XOR number?


> **Xorness** is a class of uncertainty arising from *indeterminacy, exclusivity, and
> hesitancy*.


To better understand the underlying philosophy of the concept of *Xorness* and
*XOR numbers*, consider the following example. Suppose a panel of experts is asked
to evaluate the risks to a company's sensitive data infrastructure using a 9-point
Likert scale, in which each integer corresponds to a distinct threat level ranging
from the least to the most impactful. For example, threats such as malware, phishing,
and ransomware might correspond to risk levels 4, 5, and 6, respectively. Due to the
scarcity and imperfect nature of the information, combined with the structural
complexity of cybersecurity, experts may find it challenging to be precise in
estimating specific levels of cyberthreats. Instead, they might consider a set of
potential scenarios, each representing a possible threat level. These scenarios are
typically mutually exclusive. However, one such scenario might conclude as follows:

> *"This type of cybersecurity risk will be at level 4, 5, or 6."*

The word *or* in this expression is far from incidental. In semantics, exclusive
disjunction is a form of alternation that is often employed to cope with uncertainty,
especially when responding to questions. As noted by Lindley (1962), such usage
reflects the way individuals convey a lack of knowledge or indeterminacy in their
choices. The use of exclusive disjunction in our expression is crucial because it
carries functional information about the nature and type of uncertainty. In the
cybersecurity example, removing this linguistic device from the context would result
in a loss of functional information. For a comprehensive discussion of the
philosophical significance of disjunction, the reader is referred to Jennings (1994).
Now, it might be asked why we use the word "or"[^1] to express our judgment. As
Russell (1962) noted:

> Hesitation may be observed in animals, but in them (one supposes), it does not
> find verbal expression. Human beings, seeking to express it, have invented the
> word 'or'. (p. 210)

According to the *Oxford English Dictionary*, "hesitation" is defined as the act of
pausing or delaying decision making or action due to irresolution; it also refers to
a condition of doubt in relation to action ("hesitation," 2024). Etymologically,
hesitation derives from the Latin *haesitationem*, denoting "irresolution" or
"uncertainty" (Harper, 2024).

In logic, exclusive disjunction is represented by the XOR logical operator. This
operator yields a value of *true* if and only if the operands differ, meaning that
one operand is true and the other is false. A proposition has a truth value: *true*
is denoted by the binary digit 1, and *false* is denoted by the binary digit 0. This
set of two binary values is called the Boolean domain. Many propositions in our daily
life have easily determined truth values, such as "2 < 3." However, when the truth
is indeterminate, a central philosophical subject is introduced: the nature of truth
and indeterminacy. According to the *Oxford English Dictionary*, indeterminacy refers
to something that is difficult to identify exactly ("indeterminacy," 2024). In
philosophy, there is ongoing debate about the nature of indeterminacy. One view
argues that indeterminacy has an epistemological dimension, reflecting our
limitations in obtaining definitive knowledge about certain states or properties due
to inherent uncertainties, such as those found in complex systems or in the
interpretation of language (Quine, 1960). In contrast, another perspective suggests
that indeterminacy has an ontological dimension, proposing that some aspects of
reality may lack a fixed, determinate structure — implying that the world itself may
be fundamentally indeterminate (Barnes & Williams, 2011).

Returning to the cybersecurity example: because classical logic operates within the
Boolean domain, only one of the candidate risk levels can, in actuality, be true.
Nevertheless, given the indeterminacy, treating the expression "the cybersecurity
risk will be at level 4, 5, or 6" as a *unified cognitive entity* representing the
overall risk assessment allows us to handle properly the nature of the uncertainty
inherent in such evaluations. This perspective aligns with the view of indeterminacy
as an epistemic limitation while remaining open to ontological possibilities.
Formally, the expression


$$4 \ \mathsf{XOR} \ 5 \ \mathsf{XOR} \ 6$$

represents an **XOR number**. The notions of *indeterminacy*, *exclusivity*, and
*hesitation* collectively define a type of uncertainty that is termed **Xorness**.

[^1]: Russell pointed out in *An Inquiry into Meaning and Truth* that "or" can be used in two distinct ways: as inclusive-or or exclusive-or. Inclusive-or implies that either of the two given options can be true, or that both are true simultaneously. For example, if I say, "I will have either coffee or tea," I mean that I am willing to have either coffee or tea, or both if I choose. Exclusive-or (which is the case in this study), by contrast, means that only one of the two given options can be true, and not both. For example, if I say, "You can have either coffee or tea," using exclusive-or, I mean that you may choose one of the two options but not both (Russell, 1962).

---

▶️ Learn more about Xorness in [this short video](https://www.youtube.com/watch?v=OdQ2pHoLgNc).

---

For more theoritical details, see the Hocine (2026).

---


### 📫 Where to find me

- 🌐 Website: [xorium.org](https://xorium.org)
- 🎓 [Google Scholar](https://scholar.google.com/citations?user=4T5gQj4AAAAJ&hl=en)
- 🔗 [ORCID](https://orcid.org/0000-0003-2480-5471)
- 💼 [LinkedIn](https://www.linkedin.com/in/amin-h-6bba7a265/)
- 📧 amin.hocine@unibg.it


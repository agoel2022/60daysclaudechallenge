# ABTalks 60 Days Claude Challenge – Day 03

# Role-Based Prompting: Same Question, Different Expert

Today I explored one of the simplest Prompt Engineering techniques: **Role-Based Prompting**.

The experiment was straightforward.

I asked the same question multiple times, but changed only one thing:

**The role assigned to Claude.**

---

## Baseline Experiment

### Prompt

```text
How can I improve employee retention?
```

### Response Characteristics

* Broad recommendations
* Applicable to most organizations
* General workplace advice
* Limited context-specific guidance

### Observation

The answer was reasonable but generic. Claude responded as a general-purpose assistant without a specific perspective.

### Learning

Without context, AI tends to optimize for broadly applicable answers.

---

## Experiment 1: HR Director

### Prompt

```text
You are an HR Director with 15 years of experience.

How would you improve employee retention in a growing technology company?
```

### Response Characteristics

* Career progression frameworks
* Employee engagement initiatives
* Stay interviews
* Internal mobility programs
* Manager effectiveness strategies

### Observation

The response focused on people operations and talent management practices commonly used by HR leaders.

### Learning

When given an HR leadership role, Claude prioritizes workforce and employee experience considerations.

---

## Experiment 2: Startup Founder

### Prompt

```text
You are a startup founder scaling from 50 to 200 employees.

How would you improve employee retention?
```

### Response Characteristics

* Culture preservation
* Mission alignment
* Hiring quality
* Leadership communication
* High-performer retention

### Observation

The response shifted toward challenges associated with rapid growth and scaling organizations.

### Learning

The assigned role influences not only the answer but also the business context Claude assumes.

---

## Experiment 3: CFO

### Prompt

```text
You are a CFO responsible for controlling costs while maintaining employee retention.

How would you improve retention?
```

### Response Characteristics

* Retention ROI
* Compensation optimization
* Workforce planning
* Productivity impact
* Cost-benefit analysis

### Observation

The recommendations became financially oriented and focused on measurable business outcomes.

### Learning

Different roles prioritize different success metrics.

---

## Experiment 4: Organizational Psychologist

### Prompt

```text
You are an organizational psychologist specializing in employee motivation.

How would you improve employee retention?
```

### Response Characteristics

* Motivation theory
* Recognition systems
* Psychological safety
* Employee belonging
* Autonomy and purpose

### Observation

The response focused heavily on human behavior and engagement rather than organizational processes.

### Learning

Role instructions influence which knowledge domains Claude brings forward.

---

## Comparison

| Role                        | Primary Focus                             |
| --------------------------- | ----------------------------------------- |
| General Assistant           | Broad recommendations                     |
| HR Director                 | Talent management and employee experience |
| Startup Founder             | Culture and scaling challenges            |
| CFO                         | Financial impact and ROI                  |
| Organizational Psychologist | Motivation and human behavior             |

---

## Key Learning

Role-Based Prompting works because expertise shapes perspective.

The underlying model remains the same.

What changes is:

* The assumptions Claude makes
* The frameworks it applies
* The trade-offs it considers
* The recommendations it prioritizes

---

## A Simple Formula

```text
Question
+
Role
+
Context
=
More Relevant Answers
```

---

## Day 03 Takeaway

Most users ask AI a question.

More advanced users tell AI who it should be before answering.

The difference is often the difference between a generic response and a domain-specific one.

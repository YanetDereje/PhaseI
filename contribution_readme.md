# Contribution [#180]: [Should allow setting camera properties from `<gui><camera>`]

**Contribution Number:** [1 / 2 / 3]   180 (in sheets) 573 (github)
**Student:** [Your Name] Yanet Dereje  
**Issue:** [GitHub issue link] https://github.com/gazebosim/gz-gui/issues/573 
**Status:** [Phase I / Phase II / Phase III / Phase IV] [In Progress / Complete]  Phase I Completed

---

## Why I Chose This Issue

[1-2 paragraphs explaining why this issue interests you, how it matches your skills/learning goals, what you hope to learn]

--- This issue interests me because it highlights skills that I havent had too much experience on, but also touches on C++. I love that it touches on robotics, which has always been an interest in mine, and I feel like it closely resembles my skills because this issue involves adding support for reading camera properties from a new or existing XML config tag, and so that closely aligns with my embedded systems background. I hope to learn more about config files and how to adjust and enhance these properties to be more accessible for individuals.

## Understanding the Issue

### Problem Description

[In your own words, what's broken or missing?]
what may be missing is a function in the <gui><camera> (config file) to not touch the other default plugins.

### Expected Behavior

[What should happen?]
once manually installing the plugin, it should not uninstall or turn off the other default plugins.

### Current Behavior

[What actually happens?]
if you want to configure a camera property in the software, the only way to do it is by loading a specific plugin called MinimalScene, but once you load it in manually, it turns off the other default plugins. So then it makes the process much more grueling and a waste of time.

### Affected Components

[Which parts of the codebase are involved?]

---  it involves both functions within both <gui> and <camera>.

## Reproduction Process

### Environment Setup

[Notes on setting up your local development environment - challenges you faced, how you solved them]

### Steps to Reproduce

1. [Step 1]
2. [Step 2]
3. [Observed result]

### Reproduction Evidence

- **Commit showing reproduction:** [Link to commit in your fork]
- **Screenshots/logs:** [If applicable]
- **My findings:** [What you discovered during reproduction]

---

## Solution Approach

### Analysis

[Your analysis of the root cause - what's causing the issue?]

### Proposed Solution

[High-level description of your fix approach]

### Implementation Plan

Using UMPIRE framework (adapted):

**Understand:** [Restate the problem]

**Match:** [What similar patterns/solutions exist in the codebase?]

**Plan:** [Step-by-step implementation plan]
1. [Modify file X to do Y]
2. [Add function Z]
3. [Update tests]

**Implement:** [Link to your branch/commits as you work]

**Review:** [Self-review checklist - does it follow the project's contribution guidelines?]

**Evaluate:** [How will you verify it works?]

---

## Testing Strategy

### Unit Tests

- [ ] Test case 1: [Description]
- [ ] Test case 2: [Description]
- [ ] Test case 3: [Description]

### Integration Tests

- [ ] Integration scenario 1
- [ ] Integration scenario 2

### Manual Testing

[What you tested manually and results]

---

## Implementation Notes

### Week [X] Progress

[What you built this week, challenges faced, decisions made]

### Week [Y] Progress

[Continue documenting as you work]

### Code Changes

- **Files modified:** [List]
- **Key commits:** [Links to important commits]
- **Approach decisions:** [Why you chose certain approaches]

---

## Pull Request

**PR Link:** [GitHub PR URL when submitted]

**PR Description:** [Draft or final PR description - much of the content above can be adapted]

**Maintainer Feedback:**
- [Date]: [Summary of feedback received]
- [Date]: [How you addressed it]

**Status:** [Awaiting review / Iterating / Approved / Merged]

---

## Learnings & Reflections

### Technical Skills Gained

[What you learned technically]

### Challenges Overcome

[What was hard and how you solved it]

### What I'd Do Differently Next Time

[Reflection on your process]

---

## Resources Used

- [Link to helpful documentation]
- [Tutorial or Stack Overflow post that helped]
- [GitHub issues or discussions that helped]

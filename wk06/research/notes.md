# Interview Notes — Week 6

## Participant A
**Date**: [YYYY-MM-DD HH:MM]
**Context**: [e.g., Uses keyboard only, prefers dark mode, has ADHD]
**Consent**: ✅ Confirmed verbally
**Duration**: [~10 minutes]

### Q1: Last time you used a task manager
**Response**: "I use Notion for uni work. Last week I had to find all tasks tagged 'COMP2850' to prepare for a deadline. It took ages because the filter kept resetting."

**Observations**:
- Mentioned filter UX issue (cognitive load)
- Time pressure context (deadline stress)
- Tag-based workflow (not just chronological)

**Themes**: `filter_persistence`, `cognitive_load`, `deadline_anxiety`

---

### Q2: What frustrates you?
**Response**: "When I submit a form and nothing happens—like, did it save? I have to refresh the whole page to check."

**Observations**:
- Lack of confirmation feedback
- Low trust in interface
- Workaround = page reload (inefficient)

**Themes**: `status_feedback`, `confirmation`, `trust`

---

### Q3: Lost track of important task?
**Response**: "Yeah, I once forgot to submit coursework because it was buried in my list. I wish there was a way to pin urgent things."

**Observations**:
- List length issue (visibility)
- Prioritisation need
- Consequence = missed deadline (high impact)

**Themes**: `prioritisation`, `visibility`, `urgent_tasks`

---

### Q4: Work without a mouse?
**Response**: "My trackpad broke last month. I tried using Tab to navigate, but some buttons were impossible to reach. Had to borrow a friend's mouse."

**Observations**:
- Keyboard-only experience = friction
- Temporary impairment (broken hardware)
- Exclusion from features

**Themes**: `keyboard_nav`, `temporary_impairment`, `button_accessibility`

---

### Q5: Eyes closed / bright sunlight?
**Response**: "Haven't tried eyes closed, but in sunlight I can't read low-contrast text. I increase zoom but then the layout breaks."

**Observations**:
- Contrast issue (situational disability)
- Zoom breaks responsive design
- Environmental factor (sunlight)

**Themes**: `contrast`, `zoom`, `responsive_design`

---

### Q6: One feature to add?
**Response**: "A way to see progress—like, 'You've completed 8 out of 12 tasks this week.' That would motivate me."

**Observations**:
- Motivation through feedback
- Progress visualisation
- Weekly scope (not just daily)

**Themes**: `progress_tracking`, `motivation`, `feedback`

---

## Summary (Participant A)
**Top pain points**:
1. Filter resets → cognitive overload
2. No confirmation feedback → uncertainty
3. Keyboard navigation gaps → temporary exclusion
4. Contrast issues in bright light → situational disability

**Job story ideas**:
- "When I'm filtering tasks, I want the selection to persist across page reloads so I don't lose my place."
- "When I submit a form, I want immediate confirmation so I know it worked without refreshing."
- "When my mouse breaks, I want full keyboard access so I can still complete tasks."

-----------------------------------------------------------------

## Participant B
**Date**: [YYYY-MM-DD HH:MM]
**Context**: Uses phone for almost everything
**Consent**: ✅ Confirmed verbally
**Duration**: [~10 minutes]

### Q1: Last time you used a task manager.
**Response**: "I used Tencent To Do for planning my assignments. But the reminders sometimes didn’t go off on time, so I missed a couple of things."

**Observations**:
- Rely heavily on reminders
- Mentioned delay and not-triggered notifications
- Low trust in system 

**Themes**: `reminder_reliability`, `memory_support`, 'trust'
---

### Q2: What frustrates you?
**Response**: "Sometimes I click save, nothing happens, so I click again… then it creates repeat items."

**Observations**:
- No clear save confirmation
- Repeat tasks creation due to error instructions
- Low tolerance for uncertain states

**Themes**: `status_feedback`, `repeated_items`, `confirmation`

---

### Q3: Lost track of important task?
**Response**: "Yes. I missed uploading an assignment because it was covered by older items. There was no priority or highlight"

**Observations**:
- Visibility problems
- No priority cues
- Missed assignment deadline

**Themes**: `priority`, `visibility`, `deadline_task`

---

### Q4: Work without a mouse?
**Response**: "I don’t use keyboard shortcuts. If the buttons are small, I probably won’t find them."

**Observations**:
- Mouse-dominant interaction
- Needs large, visible click targets
- Low frequency of keyboard using 

**Themes**: `pointer_accessibility`, `target_size`, `low_keyboard_use`

---

### Q5: Eyes closed / bright sunlight?
**Response**: "Outside on mobile, low-contrast text disappears unless I shade the screen."

**Observations**:
- Contrast sensitivity
- Mobile outdoor usage
- Disability on different situations

**Themes**: `contrast`, `mobile_use`, `situational_damage`

---

### Q6: One feature to add?
**Response**: "A reminder system that actually triggers on time."

**Observations**:
- Wants accurate reminders
- High time sensitivity
- 

**Themes**: `time_accuracy`, `reminder_reliability`

---

## Summary (Participant B)
**Top pain points**:
1. Reminders not reliable → missed deadlines
2. No confirmation after save → repeated items
3. No visual priority cues → items covered
4. Small buttons and low contrast → hard to click

**Job story ideas**:
- "When I add or edit a task, I want immediate confirmation so I know it succeeded without checking manually."
- "When I look for an important task, I want a clear way to surface it so it doesn't get lost in the list."
- "When I rely on reminders, I want them to work stable so I don't miss assignment deadlines."

--------------------------------------------------------------------------------------------------

## Participant C
**Date**: [YYYY-MM-DD HH:MM]
**Context**: Uses desktop for study, prefers stable UI
**Consent**: ✅ Confirmed verbally
**Duration**: [~10 minutes]

### Q1: Last time you used a task manager.
**Response**: "I used Dida To Do. Filtering doesn't announce updates, so I'm not always sure it worked"

**Observations**:
- Needs aria-live announcement
- Filter results are invisible to SR users
- System state unclear

**Themes**: `screenreader_feedback`, `filter_uncertainty`,'status'
---

### Q2: What frustrates you?
**Response**: "Sometimes buttons are not announced clearly. NVDA only says ‘button’, without telling me what it does."

**Observations**:
- Missing or unclear accessible names
- Screen reader ambiguity → user unsure of action
- Unclear actions; slower completion

**Themes**: `aria_labeling`, `ambiguous_controls`, 'unclear_actions'

---

### Q3: Lost track of important task?
**Response**: "Yes, especially when due dates are read in strange order or not grouped with titles."

**Observations**:
- Sentence structure unclear
- Due dates not announced on time
- Loss of information

**Themes**: `sentence_structure`, `deadline_remind`, `lost_info`

---

### Q4: Work without a mouse?
**Response**: "I always rely on keyboard. If tab order breaks, the UI becomes unusable."

**Observations**:
- Requires predictable focus order
- Cannot access hidden or JS-only controls
- Keyboard is primary navigation

**Themes**: `keyboard_nav`, `focus_order`, `interactive_ability`

---

### Q5: Eyes closed / bright sunlight?
**Response**: "Not applicable visually, but when focus jumps unexpectedly after an action, I lose track of where I am."

**Observations**:
- Focus management issues
- Unexpected focus movement interrupts workflow
- Lack of visual anchors increases cognitive load.

**Themes**: `focus_management`, `predictability`,'cognitive_load'

---

### Q6: One feature to add?
**Response**: "Announce success after editing—something like ‘Task updated successfully."

**Observations**:
- Desire for explicit status messages
- Needs aria-live regions
- Helps confirm actions

**Themes**: `aria_live`, `status_confirmation`, `trust`

---

## Summary (Participant C)
**Top pain points**:
- State changes not announced
- Identical Edit/Delete buttons cause confusion
- Due dates/details read inconsistently
- Tab order issues block access

**Job story ideas**:
- "When I activate a button, I want its label to clearly describe the action so I know what will happen."
- "When UI content updates (like filtering or adding tasks), I want NVDA to announce the change so I understand the new state."
- "When navigating with the keyboard, I want focus to move predictably so I don’t lose my position."
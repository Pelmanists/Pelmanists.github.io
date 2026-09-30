Assuming you are building a memory-sequencing VR experience inspired by the **Simon game** tailored for adults aged 70+, here is a complete **9-screen paper prototype and digital authoring blueprint** for ForgeXR on the Meta Quest 3.

This design merges sequence recall with a gentle morning routine (making tea/coffee), ensuring large UI targets, high-contrast visuals, gentle pacing, and low-stress error recovery.

---

### The 9-Screen VR Experience: "The Morning Melody & Routine"

| Screen # | Screen Title | Visual Layout & UI Elements | User Interaction / Action | State Transition |
| --- | --- | --- | --- | --- |
| **1** | **Welcome & Orientation** | Large, high-contrast text on a warm wooden background ("Welcome! Let's warm up your memory today."). Audio voiceover speaks slowly. A giant "Start" button pulses gently. | User points the Quest controller or uses hand tracking to tap the **Start** button. | Transitions to Screen 2 on button click. |
| **2** | **Tutorial: Watch & Learn** | A friendly virtual guide appears. Three large, glowing colored orbs (Red, Blue, Yellow) float at comfortable chest height. Text: "Watch the pattern carefully." | User watches as the orbs light up in a simple 2-step sequence (e.g., Red $\rightarrow$ Blue) with soft chimes. | Auto-advances to Screen 3 once the demonstration ends. |
| **3** | **Your Turn: Level 1** | The same 3 glowing orbs are active. Text prompts: "Your turn! Repeat the pattern." | User taps the orbs in the correct sequence (Red, then Blue). | **Success:** Goes to Screen 4. **Mistake:** Triggers a gentle voice ("Let's try that one more time") and repeats the prompt without penalty. |
| **4** | **Routine Transition** | The environment shifts gently to a cozy kitchen counter. Text: "Great job! Now let's prep your morning tea. Remember the steps." | User views 3 large item icons on the counter: Kettle, Mug, Tea Bag. | Auto-advances after 5 seconds or when the user taps "Continue". |
| **5** | **Recipe Sequence: Watch** | The 3 kitchen items light up in a specific order with a distinct sound for each (e.g., Kettle $\rightarrow$ Tea Bag $\rightarrow$ Mug). | User watches the 3-step sequence. | Auto-advances to Screen 6. |
| **6** | **Recipe Sequence: Your Turn** | Text prompt: "Tap the items in the order you saw." The items remain large and high-contrast. | User taps the Kettle, Tea Bag, and Mug in the correct sequence. | **Success:** Goes to Screen 7. **Mistake:** Gentle audio cue ("Almost! Let's review the steps together") and a quick re-demonstration. |
| **7** | **Memory Challenge: Level 3** | The environment opens slightly. The system introduces a slightly longer 4-step sequence combining colors and sounds (e.g., Blue $\rightarrow$ Yellow $\rightarrow$ Red $\rightarrow$ Blue). | User watches and repeats the 4-step sequence. | **Success:** Goes to Screen 8. **Mistake:** Encouraging soft chime, offers a "Hint" button before retrying. |
| **8** | **Celebration & Summary** | Confetti animation (low-motion, gentle floating bubbles) and a soft congratulatory chime. Text: "Wonderful job keeping your memory sharp today!" | User views their accomplishment summary. Large "Finish" or "Play Again" button appears. | Transitions to Screen 9 on button click. |
| **9** | **Goodbye & Exit** | Calming landscape view. Text: "You've completed today's session. Have a wonderful day!" A button to safely exit or restart. | User selects "Exit" to close the session or remove the headset. | Session concludes / saves progress. |

---

### Key Design Elements Built-In for Ages 70+

* **Low-Stress Error Recovery:** If a user fails on Screens 3, 6, or 7, the experience *never* locks them out or punishes them. It offers immediate, encouraging encouragement and replays the prompt.
* **Ergonomics:** All interactive targets (orbs, kitchen items) are positioned directly in front of the user at chest-to-eye level to prevent neck strain or excessive reaching.
* **Multisensory Cues:** Every visual flash is paired with a distinct audio tone, aiding users with mild visual or auditory impairments.

---


### Example: filled for the VR memory-sequencing scenario

| Field | Value |
| --- | --- |
| **Course Name** | Human-Centered XR Design |
| **Scenario Title** | The Morning Melody & Routine |
| **Subject Area / Domain** | Computer Science |
| **Scenario Difficulty** | Beginner |
| **Estimated Duration** | 10–15 minutes |

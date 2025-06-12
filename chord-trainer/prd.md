<!-- Output copied to clipboard! -->

<!-----
NEW: Check the "Suppress top comment" to remove this info from the output.

Conversion time: 1.34 seconds.


Using this Markdown file:

1. Cut and paste this output into your source file.
2. See the notes and action items below regarding this conversion run.
3. Check the rendered output (headings, lists, code blocks, tables) for proper
   formatting and use a linkchecker before you publish this page.

Conversion notes:

* GDC version 1.1.19 r36
* Thu Jun 12 2025 01:00:28 GMT-0700 (Pacific Daylight Time)
* Source doc: https://docs.google.com/open?id=13qCefs92EQdyfuvqu2HZqJV-bD6jpQW_fkUPWLdrIfA&resourcekey=0-OzuU2XKNK1vp0jyk_Mx7DA
----->



# **Product Requirements Document: Configurable Ear Trainer**

Author: Gemini

Date: June 12, 2025

Version: 1.0


## **1. Introduction**


### **1.1. Problem Statement**

Musicians and music students need a flexible and effective way to practice aural skills, specifically chord recognition within a musical key. Existing tools are often too rigid, lack customization, or require constant manual interaction, which disrupts the learning flow. This makes "hands-free" practice, such as during a commute or while holding an instrument, nearly impossible.


### **1.2. Proposed Solution**

The **Configurable Ear Trainer** is a web-based application designed to provide a "hands-free," highly customizable aural training experience. It allows users to create personalized quizzes by selecting a key, a scale, and the specific diatonic chords and their variations they wish to practice. The application plays a chord, pauses for a user-defined duration, and then announces the answer, creating a continuous and focused training loop.


### **1.3. Goals**



*   **Improve Aural Skills:** To provide an effective tool for musicians to improve their ability to recognize diatonic chords and their qualities by ear.
*   **Enable Focused Practice:** To allow users to isolate specific chords, scales, and variations they find challenging.
*   **Provide a Hands-Free Experience:** To enable continuous learning without requiring the user to look at or touch their device after starting a session.
*   **Enhance Usability:** To create a simple, intuitive interface that remembers user preferences for a seamless experience.


## **2. Target Audience & User Personas**



*   **Music Students:** University or private lesson students who need to pass aural skills exams and build a foundational understanding of music theory.
*   **Self-Taught Musicians & Hobbyists:** Guitarists, pianists, and other instrumentalists who want to improve their ability to play by ear, learn songs faster, and understand chord progressions.
*   **Songwriters and Producers:** Creative musicians who want to internalize the sound of different chord qualities to improve their compositional toolkit.


## **3. User Stories & Core Features**


### **3.1. Core Experience: The Training Loop**

|

| As a... | I want to... | So that I can... |

| User | start a training session that plays a random chord from my selected pool | practice identifying chords by ear. |

| User | hear the name of the chord announced after a delay | check my answer without looking at the screen. |

| User | have the quiz loop continuously | practice for an extended period without interruption. |


### **3.2. Feature: Key & Scale Configuration**

| As a... | I want to... | So that I can... |

| User | select any of the 12 chromatic notes as the key | practice in any tonal center. |

| User | choose from a list of common scales (Major, Natural/Harmonic/Melodic Minor) | train my ear for the specific sound of different modes. |


### **3.3. Feature: Diatonic Chord Selection**

| As a... | I want to... | So that I can... |

| User | see a list of the 7 diatonic chords for my chosen key/scale | understand the basic harmonic structure. |

| User | select which of the 7 diatonic chords to include in the quiz | focus my practice on specific scale degrees (e.g., just V and I). |


### **3.4. Feature: Chord Variation Selection**

| As a... | I want to... | So that I can... |

| User | choose different "versions" for each diatonic chord (e.g., Major, minor, aug, dim, sus2/4, 7ths) | learn to distinguish between different chord qualities built on the same root. |

| User | enable different inversions (root, 1st, 2nd) for each selected chord | learn to recognize chords when the bass note is not the root. |


### **3.5. Feature: Session Customization**

| As a... | I want to... | So that I can... |

| User | set the delay time (in seconds) between the chord playing and the answer being announced | give myself enough time to think, or challenge myself with a shorter delay. |

| User | hear a key calibration sequence (arpeggio and tonic chord) at the start of a session | firmly establish the tonal center in my ear before the quiz begins. |

| User | hear a verbal cue ("Start training") after the calibration | know exactly when the quiz is about to start. |


### **3.6. Feature: Settings Persistence**

| As a... | I want to... | So that I can... |

| User | have all my configuration settings (key, scale, chords, delay) automatically saved in my browser | quickly resume my preferred training session without setting it up again each time. |


## **4. Non-Functional Requirements**



*   **Usability:** The interface must be clean, intuitive, and easy to navigate on both desktop and mobile devices. All configuration options should be clearly labeled.
*   **Performance:** The application must be responsive. Audio playback should be instantaneous upon user action. The UI should update smoothly without lag.
*   **Accessibility:** The application should use clear color contrast for text and controls. Spoken answers provide an essential layer of accessibility.
*   **Browser Compatibility:** The application must function correctly on the latest versions of major web browsers (Chrome, Firefox, Safari, Edge).


## **5. Future Enhancements (Potential v2.0 Features)**



*   **Expanded Content:**
    *   More scales (e.g., Dorian, Mixolydian, Pentatonic).
    *   More chord variations (e.g., 9ths, 11ths, 13ths, altered dominants).
    *   Advanced chord voicings and more complex inversions.
*   **Gamification & Progress Tracking:**
    *   A "Quiz Mode" where the user has to identify the chord, with scoring and statistics.
    *   Visual progress charts to show improvement over time.
    *   Level-based progression that introduces new concepts gradually.
*   **Instrument Sound Selection:**
    *   Allow the user to change the synth sound to a more realistic piano or guitar sound.

# SignBridge — UI Design Mockup Sequence

This document outlines the high-fidelity UI mockups for the SignBridge application, presented in the exact sequential order (Step 1 to Step 10) that a user would experience them.

At the very end of this document is the **Visual User Flow Map** tying all these screens together.

---

## Step 1: The Landing Page
*The entry point for all new visitors. Communicates the core value and starts the journey.*
![Landing Page](UI_Mockups/landing_page_1781466865909.png)

## Step 2: About / Mission
*Establishing trust and emotional connection by explaining the "Why" behind the app.*
![About and Mission](UI_Mockups/about_mission_page_1781466997938.png)

## Step 3: Customer Login & Preference Setup
*Where the user creates their account, selects their role (Deaf/Hearing), and sets primary language/dialect.*
![Customer Login and Preference Setup](UI_Mockups/customer_onboarding_1781467226931.png)

## Step 4: First-Time Onboarding Wizard
*A one-time flow that guides the user through securely granting camera and microphone permissions.*
![Onboarding Flow](UI_Mockups/onboarding_flow_1781466986255.png)

## Step 5: The Interaction Hub (Main App)
*The core application dashboard where real-time two-way translation (Voice-to-Sign / Sign-to-Voice) occurs.*
![Interaction Hub](UI_Mockups/interaction_hub_1781466877011.png)

## Step 6: Control Panel & Settings
*Accessed from the Hub. Allows users to switch dialects, apply context presets (e.g., Medical), and customize their avatar.*
![Control Panel](UI_Mockups/control_panel_1781466888679.png)

## Step 7: History & Phrasebook
*Where users review saved translations, conversation logs, and replay specific signs back on the Interaction Hub.*
![History and Phrasebook](UI_Mockups/history_phrasebook_1781466924361.png)

## Step 8: Admin Dictionary Editor (Hidden)
*The backend interface where administrators map new words and synonyms to specific 3D sign animations.*
![Admin Dictionary Editor](UI_Mockups/admin_dictionary_editor_1781467240899.png)

## Step 9: Admin Gesture Data Collector (Hidden)
*The tool used by your ML team to record webcam tracking coordinates via MediaPipe for custom AI model training.*
![Admin Gesture Collector](UI_Mockups/admin_gesture_collector_1781467257224.png)

## Step 10: Developer Dashboard (Hidden)
*Where your team monitors latency, MediaPipe frame rates, and model retraining progress.*
![Developer Dashboard](UI_Mockups/dev_dashboard_1781466936855.png)

## Bonus: Mobile Responsiveness
*How the primary views from the steps above adapt to smartphone screens.*
![Mobile Responsiveness](UI_Mockups/mobile_responsive_1781466949644.png)

---

## Final Architecture: Visual User Flow Map
*This is the zoomed-out blueprint showing exactly how all the screens above connect to each other from beginning to end.*

![Visual User Flow Map](UI_Mockups/visual_user_flow_map_1781468415127.png)

# Blue Ember Wellness Reiki Academy — Project Brief & Build Handoff

**Prepared:** October 30, 2026  
**Status:** Requirements collected; third-party app builder link prepared. No completed or deployed app has been verified.  
**Project:** Blue Ember Wellness Reiki Academy  
**Parent brand:** Blue Ember Wellness  
**Primary brand website:** https://BlueEmberWellnessRVA.com  
**Local asset folder identified by user:** `D:\__BlueEmberWellness` (not accessed)

## 1. Purpose and scope

Build a **mobile app for iOS and Android** named **Blue Ember Wellness Reiki Academy** to support the *in-person* Reiki education program of Blue Ember Wellness. The app is for reference materials and student management, **not an online Reiki school**.

**Instructor:** Reiki Master **Mark Kantner**. All Reiki Levels 1, 2, and 3 formal instruction, attunements, assessments, and certifications take place exclusively in person under Mark's direct authority. App activity cannot itself confer a Reiki level or certification.

## 2. Confirmed decisions from the planning conversation

1. **Roles:** Students have private mobile accounts; Mark has a private instructor/administrator dashboard.
2. **Student registration:** Students may self-register, but their enrollment is pending until Mark approves it.
3. **Level progression:** Mark personally unlocks access to Reiki Levels 1, 2, and 3.
4. **Student features (all selected):**
   - Read level-specific reference materials and study guides approved for student viewing.
   - View in-person class schedules and attendance.
   - Track approved training milestones and Reiki level.
   - View certificates issued by Mark after in-person completion.
   - Keep a private Reiki practice journal.
   - Receive announcements and messages from Mark.
5. **Complete instructor records:** Mark logs in-person attunement dates, attendance, assessment results, private notes, and certification approvals.
6. **Confidentiality:** Students see only approved milestones and issued certificates; private instructor notes and internal assessments stay restricted to Mark.
7. **Teaching-library governance:** Organize materials with the uploaded *Reiki Master Teacher Material — Higher Power Edition* as a key source, and require Mark's approval before content becomes student-visible.
8. **Brand assets:** Use genuine Blue Ember Wellness logos and appropriate photography uploaded by the owner, rather than generating a substitute business logo.

## 3. Brand and visual design

**Primary visual authority:** The existing site at https://BlueEmberWellnessRVA.com. Branding must match that website as closely as the supplied assets permit, including official logo, actual color values, typography, spacing, visual tone, and imagery.

**Known design direction:** Deep navy-blue backgrounds, luminous turquoise accents, subtle gold details, and polished typography. Calm, respectful, refined look. Use **clothed clients** in all photos and illustrations, in settings consistent with Reiki energy work. Avoid imagery of massage oils, hot stones, unclothed clients, or unrelated massage/spa services.

**Asset source identified:** `D:\__BlueEmberWellness` on the user's Windows computer. This folder has **not** been accessed or imported. No site-specific font names, exact hex values, or official logos have been verified in this conversation.

## 4. Proposed product structure

The following screens and system components were included in the app builder handoff prompt (implementation not yet verified):

### Student experience
- Welcome/onboarding and login
- Registration and pending-approval state
- Private student dashboard
- Approved, level-gated study/reference library
- In-person class calendar and attendance
- Approved progress milestones and Reiki level
- Private practice journal
- Issued certificates
- Announcements and instructor messages
- Student profile

### Mark's instructor/admin experience
- Private admin dashboard
- Registration-approval queue and student account management
- Enrollment and Reiki-level permission controls
- Class scheduling and attendance tracking
- In-person attunement recordkeeping
- In-person assessment records and confidential notes
- Manual milestone and certification approval
- Approval/publishing controls for student-facing teaching content
- Student messaging and announcements

### Data and permissions
- Secure authentication and private student accounts
- Role-based data access: instructor vs. student
- Level-specific library access
- Instructor-only confidential records
- Student-private journals
- Certification records must be explicitly authorized by Mark
- Accessibility and privacy protections

## 5. Source materials supplied

The user uploaded both formats of:

- `Reiki Master Teacher Material - Higher Power Edition.docx`
- `Reiki Master Teacher Material - Higher Power Edition.pdf`

**Notable source-derived guidance (from supplied document excerpt):**
- The edition is authored/presented by Mark Kantner of Blue Ember Wellness and dated October 21, 2026.
- Mark describes the Higher Power Edition as a **companion**, not a replacement, to material received from teacher **Mary Gaston** on October 18, 2026.
- It intentionally uses inclusive **Higher Power / Higher Self** spiritual language, treating Reiki as a personal spiritual practice rather than a religion.
- It contains sections concerning becoming a Reiki Master, teaching with integrity, choosing teachers, preparing to teach, questions for teachers, and detailed attunement procedures.
- The document credits an article adapted/condensed from **William Lee Rand** and identifies a **Copyright © 2000 The Healing Arts Center** notice on attunement pages. Any publication or distribution should respect rights and attribution; Mark should review what may be shown to students.
- In its own editorial notes, the edition flags language about people creating their own misfortune as potentially problematic for a medical Reiki audience. Student-facing content should receive thoughtful instructor review rather than automatically republishing every passage.
- Detailed attunement procedures should be treated as **instructor-controlled material** within this app, not as online initiation or self-certification instructions.

**Source files are attachments in the ChatGPT conversation; this Markdown file does not embed their complete text or automatically make them available to the third-party app builder.** Upload them separately to the builder if appropriate.

## 6. Confirmed boundaries / acceptance criteria

- No online attunement, remote certification, or app-based training completion that substitutes for in-person sessions.
- No automatic level advancement: only Mark grants levels.
- No student ability to issue/edit certificates or instructor notes.
- A student cannot view content for a level Mark has not unlocked.
- All student-visible study content requires Mark's review/approval.
- Respect parent-company visual identity.
- Avoid presenting Reiki as massage or making unsupported medical treatment claims.

## 7. External build setup

A build link was generated for **Blue Ember Reiki Academy mobile app** on Emergent, using an **Expo mobile app** project type. The link preloads a detailed prompt reflecting the decisions above.

**Important:** Generation of this link is not proof of a working app, deployed preview, completed accounts, imported documents, or verified branding. The user was viewing `https://app.emergent.sh/chat` in an in-app browser; whether a project has begun building was not confirmed.

**Emergent build link:**  
https://get.emergent.sh/airesearchplus?utm_source=affiliate&utm_medium=gptapps&utm_campaign=websitegpt&sid1=GPTapp2&category=expo&project=Blue+Ember+Reiki+Academy+mobile+app&h1=Creating+your&h2=new+project&prompt=Build+Blue+Ember+Wellness+Reiki+Academy%2C+an+iOS+and+Android+mobile+app+for+Blue+Ember+Wellness%27s+in-person+Reiki+education+program+led+exclusively+by+Reiki+Master+Mark+Kantner.+Provide+student+registration+pending+Mark%27s+approval%2C+secure+private+student+accounts%2C+level-specific+access+for+Reiki+Levels+1%2C+2+and+3%2C+a+private+instructor+admin+dashboard%2C+and+instructor-controlled+enrollment+and+level+advancement.+Students+can+read+approved+level-specific+references+and+study+guides%2C+see+in-person+class+schedules+and+attendance%2C+track+approved+training+milestones%2C+view+certificates+issued+by+Mark+after+in-person+completion%2C+keep+private+Reiki+practice+journals%2C+and+receive+announcements+and+messages+from+Mark.+Mark+manages+class+enrollment%2C+attendance%2C+in-person+attunement+dates%2C+assessment+results%2C+confidential+notes%2C+milestones%2C+and+manual+certification+authorization%3B+all+formal+teaching%2C+attunements%2C+assessments%2C+and+certification+occur+exclusively+in+person%2C+never+online.+Build+a+source-document-based+teaching+library+organized+around+the+Reiki+Master+Teacher+Material+%E2%80%94+Higher+Power+Edition%2C+with+review+and+approval+controls+for+student-facing+content%2C+respectful+attribution%2C+and+careful+separation+of+instructor-only+attunement+instructions.+Follow+authentic+Blue+Ember+Wellness+branding+with+navy+backgrounds%2C+luminous+turquoise%2C+subtle+gold+accents%2C+elegant+polished+typography%2C+and+upload+controls+for+official+logos+and+clothed-client+photography+in+calm+respectful+Reiki+settings%2C+excluding+massage-style+visuals.+Include+onboarding%2C+login%2C+pending+approval%2C+student+dashboard%2C+study+library%2C+class+schedule%2C+milestones%2C+journal%2C+certificates%2C+messages%2C+profile%2C+admin+dashboard+and+student+detail+screens%2C+secure+role-based+database+permissions%2C+privacy+controls%2C+and+accessibility.

## 8. Items still to confirm / supply

- Authentic logos, brand color codes, fonts and approved images, ideally from `D:\__BlueEmberWellness`.
- Exact design tokens after examining the existing website or assets.
- Whether the uploaded Higher Power Edition has been imported into the builder and what Mark approves for each level.
- Class schedules, class locations, attendance policies, assessment rubrics and certificate templates.
- Account security, backups, retention policy, consent and privacy text, notification delivery.
- Actual project build status, functional testing and distribution to Apple App Store / Google Play.
- Any additional production integrations and operational preferences.

## 9. Suggested immediate handoff instructions for the builder

> Build and verify an iOS and Android app with two role types: instructor Mark Kantner and registered students. Match the official BlueEmberWellnessRVA.com brand using authentic owner-supplied assets from D:\__BlueEmberWellness. All teaching, attunements, assessments and certification happen only in person. Implement pending account approvals, instructor-controlled levels 1–3, a secure student library, schedules, attendance, progress, practice journals, issued certificates, announcements/messages, and a restricted admin dashboard with private attunement, assessment and certification records. Use the Higher Power Edition for the reference library only after Mark reviews and approves student-facing excerpts, preserving attribution and keeping attunement instructions instructor-only. Verify role-based data permissions and keep the app's visual content true to respectful Reiki practice.

---

*This is a consolidated project brief based on the conversation and source excerpts, not a claim that the app itself has already been built.*

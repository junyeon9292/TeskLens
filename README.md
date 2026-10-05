# TaskLens v1.5

Language-stability release. Supported UI/content languages: English, Korean, Spanish, Simplified Chinese. Japanese was removed. Language changes are atomic: all assignments are localized in one server request, and the visible language changes only after the complete response succeeds.


## v1.7
- Real API-bound spinners for assignment analysis, translation, chat, and Final Review.
- Final Review returns a 0–100 Assignment Readiness estimate (not a predicted grade).
- Translation remains per-assignment and cached by language.
- Supported languages: English, Korean, Spanish, Chinese.

# AIED Blind Paper 379
This repository supports the AIED 2026 submission: An AI-driven and Closed-loop Human Tutor Training and Real-life Assessment System.

## 📄 Summary
This study presents an AI-driven, “closed-loop” tutor training and assessment system designed to both train human tutors using scenario-based lessons and evaluate whether those learned skills actually transfer into real-life tutoring sessions. The study involved 86 remote math tutors who completed six scenario-based lessons targeting specific tutor moves. To test whether training predicts real-life performance, 405 transcript-lesson pairs were matched and analyzed using mixed-effects models.

Key findings include:
* Tutors demonstrated an overall 7.4% (p<0.5) learning gain from pretest to posttest across lessons.
* Better training performance significantly predicted better real-life transcript performance, with an effect size of 0.25 SD.
* An interrupted time series analysis suggested that improvements in tutoring quality were mostly part of a gradual upward trend over time, rather than a sharp improvement caused immediately by the training intervention.

## 📂 Repository Contents
* ```Human Open Response Scoring Rubrics```-- The codebooks for human annotators evaluating tutor open-response answers
* ```Inter-rater Reliability```-- Cohen's kappa scores measuring human-to-human and human-to-LLM agreement for tutor open-response answer scoring, transcript opportunity and transcript evaluation scoring
* ```LLM Prompts```-- The prompts provided to Gemini-2.5-pro to evaluate tutor open response answers for each lesson
* ```Lessons``` -- The lesson material provided to the tutors
* ```Open Response Scoring Notebooks```-- Code evaluating tutor open-response answers using the provided prompt
* ```Tutor Evaluation in Transcripts```-- Code evaluating tutor session transcripts for tutor moves
* ```Example of LLM-Generated Feedback.pdf```-- An example of what LLM-feedback within a lesson looks like when a tutor submits an open-response answer

##  📊 Data Access
Samples of data including lesson data and tutor transcriptions can be accessed in Datashop at https://pslcdatashop.web.cmu.edu/DatasetInfo?datasetId=6815. Note: you must create or use a pre-existing Datashop account for access.

# LLM_Bars

My team and I had a few thousand "Near Miss" events from the [Mine Safety and Health Administration](https://www.msha.gov/) and we wanted to see if we could classify "how dangerous" they were using humans and compare that to using LLMs. We queried a few dozen undergraduate students for their opinion about the incident text describing what happened and store those results. We took a sample of the "most dangerous" and "safest" incidents and submitted those to ChatGPT both with and without a [temperature parameter](https://platform.openai.com/docs/api-reference/audio/createTranscription#audio-createtranscription-temperature). In going through the results, there were ways to analyze the comparison numerically, but a visual element is always a good idea.

The query system for the undergraduate opinions was Qualtrics. Most of our processing was done in a Jupyter Notebook. This visual was created in R using the `geom_tile` function inside `ggplot`.



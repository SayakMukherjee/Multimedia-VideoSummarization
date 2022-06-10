# Looking Deeper into Multimodal Video Summarization

Video content generation and consumption have seen exponential growth in recent years. The massive amount of video data on the web affects the end-user experience who is looking for the relevant information with limited browsing time. This exacerbates the need for effective video summarization leading to a growing interest in the corresponding research domain. Most of the works currently focus on using uni-modal or bi-modal information such as video frames, audio and subtitles to formulate the video summary. However, each modality imparts a different perspective for a video, like audio can enhance the information conveyed by the visuals, and subtitles assist in following the audio. Hence it can be argued that considering multiple modalities can offer an opportunity to generate effective video summaries. Therefore, in this research, we are interested in exploring if multiple modalities can lead to better-informed summaries. For this study, we will examine the impact of visual, audio, subtitles and video title for video summarization. <br><br>

Furthermore, the previous works for bi-modal or multi-modal video summarization do not explicitly state the impact of each modality in the summarization process. Some researches include an ablation study, but it does not capture whether each modality imparts additional information that is not already captured by some other modality. It is an exciting question for investigation as it can help develop more robust systems in the future. Additionally, acquiring and processing each additional modality is resource expensive increases latency. Inspired by the research in deep metric learning, we decided to look at the projected embedding space of the features to answer the question of the relevance of each modality. This research provides a new outlook on the video summarization task to move towards more informative and less costly summaries by using only the components which provide essential insights.

## Implementation Details

The code has been tested on a free Google Colab Environment with GPU. The requirements file for creating the associated environments are included in the accompanying python notebooks. <br><br>

Order to run:
<ol>
    <li>Multimedia.ipynb - Contains code for audio, video and textual feature extraction along with caption generation</li>
    <li>Annotations.ipynb - Contains code for aggregating the scores from multiple crowd workers per video</li>
    <li>FinalProject.ipynb - Contains code for the hierarchial multimodal fusion and classification modules along with evaluation</li>
</ol>
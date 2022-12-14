# Awesome ChatGPT

This is a small document containing interesting demos / analysis done on top of ChatGPT.

Here is the list of sections in this document:

1. Cool Demos
2. Analysis / Failure Cases
3. Twitter Threads
4. ChatGPT Utilities
5. ChatGPT News

We refer to a detailed list of Twitter threads covering a large veriety of these use-cases at the bottom.


## Cool Demos

- ChatGPT explaining bugs in the code
  - https://twitter.com/amasad/status/1598042665375105024?s=20&t=vCy1yu328mi0ae9JCOHaQw
    ![](images/find_explain_bug.png '')

- ChatGPT can help detect security vulnerabilities
  - https://twitter.com/mazen160/status/1598351725756301313?s=20&t=vCy1yu328mi0ae9JCOHaQw
    ![](images/security_vulnerability.png '')

- Build a complete virtual machine inside ChatGPT, with access to terminal
  - https://www.engraved.blog/building-a-virtual-machine-inside/
    ![](images/vm_terminal_1.png '')
    ![](images/vm_terminal_2.png '')
    ![](images/vm_terminal_3.png '')
    ![](images/vm_terminal_4.png '')
    ![](images/vm_terminal_5.png '')
    ![](images/vm_terminal_6.png '')
    ![](images/vm_terminal_7.png '')

- Generate appropriate prompts for text-to-image generation models
  - https://twitter.com/GuyP/status/1598020781065527296?s=20&t=vCy1yu328mi0ae9JCOHaQw
    ![](images/text2img_room_decoration.png '')
    ![](images/text2img_room_decoration_gen.png '')

- Write a web-scraping app in streamlit
  - https://twitter.com/DataChaz/status/1599163972703645696?s=20&t=vCy1yu328mi0ae9JCOHaQw
    ![](images/streamlit_web_scrapper.png '')

- Creative writing collaboration
  - https://andrewmayneblog.wordpress.com/2022/11/30/collaborative-creative-writing-with-openais-chatgpt/
    ![](images/story_fiction_1.png '')
    ![](images/story_fiction_2.png '')
    ![](images/story_fiction_3.png '')

- Generate regular expressions
  - https://twitter.com/DataChaz/status/1599522274389807104?s=20&t=vCy1yu328mi0ae9JCOHaQw
    ![](images/regex.png '')

- Generate Youtube scripts using ChatGPT
  - https://twitter.com/1littlecoder/status/1599706368105394177?s=20&t=vCy1yu328mi0ae9JCOHaQw
    ![](images/image8.png '')

- Explain code via incorporating styles from people with different backgrounds
  - https://twitter.com/goodside/status/1598129631609380864?s=20&t=vCy1yu328mi0ae9JCOHaQw
    ![](images/youtube_transcripts.png '')

- Using ChatGPT as a postgres database
  - https://twitter.com/ankrgyl/status/1599539317332140032?s=20&t=vCy1yu328mi0ae9JCOHaQw
    ![](images/postgres_db_1.png '')
    ![](images/postgres_db_2.png '')

- Generate websites using ChatGPT featuring chatGPT and text-to-image generated content
  - https://twitter.com/DataChaz/status/1598845712975872000?s=20&t=vCy1yu328mi0ae9JCOHaQw
    ![](images/gen_cooking_website.png '')

- Generating synthetic / fake datasets
  - https://twitter.com/jrieke/status/1598843863619481605?s=20&t=vCy1yu328mi0ae9JCOHaQw
    ![](images/synthetic_csv_1.png '')
    ![](images/synthetic_csv_2.png '')

- Create a complete diet and weight loss plan using ChatGPT
  - https://twitter.com/anothercohen/status/1599531037570502656?s=20&t=vCy1yu328mi0ae9JCOHaQw
    ![](images/tdee_1.png '')
    ![](images/tdee_2.png '')
    ![](images/tdee_3.png '')

- Use ChatGPT to generate music
  - https://twitter.com/teropa/status/1598713756074246145?s=20&t=vCy1yu328mi0ae9JCOHaQw
    ![](images/ambient_music.png '')

- Ask ChatGPT to fix broken HTML
  - https://twitter.com/GregBernhardt4/status/1598819609519394816?s=20&t=vCy1yu328mi0ae9JCOHaQw
    ![](images/fix_html.png '')

- Use ChatGPT to prepare for ML interviews
  - https://twitter.com/omarsar0/status/1599874508541743104?s=20&t=vCy1yu328mi0ae9JCOHaQw
    ![](images/ml_interview_1.png '')
    ![](images/ml_interview_2.png '')
    ![](images/ml_interview_3.png '')

- Generate American flag using ChatGPT
  - https://twitter.com/goodside/status/1599873570431434752?s=20&t=vCy1yu328mi0ae9JCOHaQw
    ![](images/gen_flag.png '')

- Attempted Political Topology quiz -- ChatGPT demonstrated moderate left-learning political oritentation
  - https://twitter.com/DavidRozado/status/1599731435275157506?s=20&t=vCy1yu328mi0ae9JCOHaQw
    ![](images/political_orientation.png '')

- Demonstrated that ChatGPT removes all strings of form <|foobar|> without any spaces in the sequence
  - https://twitter.com/goodside/status/1599784399331262464?s=20&t=vCy1yu328mi0ae9JCOHaQw
    ![](images/text_ignore.png '')
  - Successfully reproduced
    ![](images/text_ignore_reprod.png '')

- Similar to “how to sporgel a morgel” example sometime ago where you can program ChatGPT to respond with a particular phrase when it doesn’t want to answer the given question
  - https://twitter.com/hi_frye/status/1599537366368411649?s=20&t=vCy1yu328mi0ae9JCOHaQw
    ![](images/noot_noot.png '')
  - Successfully reproduced
    ![](images/noot_noot_reprod.png '')

- ChatGPT can be used to write a Twitter bot
  - https://medium.com/@rlodha1/how-i-used-chat-gpt-to-build-a-twitter-bot-without-any-programming-language-35bbc43f6ad
    ![](images/twitter_bot.png '')

- Asking ChatGPT for responses as an engineer under the fear of being fired by Elon Musk if you didn’t produce enough code
  - https://twitter.com/ChatGPTGoneWild/status/1599961082558545921?s=20&t=vCy1yu328mi0ae9JCOHaQw
    ![](images/email_elon.png '')

- Asking ChatGPT regarding the fastest marine animal -- fails in an interesting way
  - https://twitter.com/ChatGPTGoneWild/status/1599795626866520069?s=20&t=kjGUWpBdhBwLdVhfR9VxEg
    ![](images/fastest_marine_mammal.png '')

- Use ChatGPT instead of going to a credit repair lawyer
  - https://twitter.com/jbrowder1/status/1599812828793556993?s=20&t=vCy1yu328mi0ae9JCOHaQw
    ![](images/credit_repair_lawyer.png '')

- Use ChatGPT to attempt a full SAT test exam -- attained 52nd percentile
  - https://twitter.com/davidtsong/status/1598767389390573569?s=20&t=AOTnLO7DxrVAiOPDhc969A
    ![](images/sat_exam.png '')

- Suggesting and writing grant proposals
  - https://twitter.com/RobLanfear/status/1599495864976027648?s=20&t=vCy1yu328mi0ae9JCOHaQw
    ![](images/grant_writing_1.png '')
    ![](images/grant_writing_2.png '')

- ChatGPT passed the 2022 AP Computer Science exam
  - https://twitter.com/t3dotgg/status/1599551203683467264?s=20&t=vCy1yu328mi0ae9JCOHaQw
  - https://gist.github.com/Gaelan/cf5ae4a1e9d8d64cb0b732cf3a38e04a
    ![](images/ap_cs_exam.png '')

- Use ChatGPT to write a wordpress plugin
  - https://twitter.com/johnofhousejohn/status/1599932681076473856?s=20&t=7jAbTF0cSLM1H9rt9NCqew
    ![](images/wordpress_plugin.png '')

- Use ChatGPT to write a rap about exploiting a buffer overflow
  - https://twitter.com/LiveOverflow/status/1599669777361825794?s=20&t=7jAbTF0cSLM1H9rt9NCqew
    ![](images/rap_buffer_overflow.png '')

- Used ChatGPT to write cold email to recruiters
  - https://twitter.com/archiexzzz/status/1599677498274766848?s=20&t=7jAbTF0cSLM1H9rt9NCqew
    ![](images/email_recruiter.png '')

- Use ChatGPT to generate UI options
  - https://twitter.com/hakimel/status/1599711644929740800?s=20&t=7jAbTF0cSLM1H9rt9NCqew
    ![](images/gen_ui_options.png '')

- ChatGPT understands / responds correctly in Hindi (an Indian language)
  - https://twitter.com/PrabhjotSL/status/1600053416029720576?s=20&t=7jAbTF0cSLM1H9rt9NCqew
    ![](images/response_hindi_1.png '')
    ![](images/response_hindi_2.png '')

- ChatGPT clones the ChatGPT repo
  - https://twitter.com/quasimondo/status/1599678917039620096?s=20&t=7jAbTF0cSLM1H9rt9NCqew
    ![](images/simulate_terminal_1.png '')
    ![](images/simulate_terminal_2.png '')
    ![](images/simulate_terminal_3.png '')
  - Failed to reproduce
    ![](images/simulate_terminal_fail.png '')
  - Simulate terminal command doesn’t work

- ChatGPT can understand implicatures
  - https://twitter.com/LauraRuis/status/1599497977173008384?s=20&t=vCy1yu328mi0ae9JCOHaQw
    ![](images/implicatures_1.png '')
    ![](images/implicatures_2.png '')
    ![](images/implicatures_3.png '')

- ChatGPT narrates the story of Jesus’ crucifixion in the style of a sportscaster
  - https://twitter.com/GanWeaving/status/1599838283550244864?s=20&t=7jAbTF0cSLM1H9rt9NCqew
    ![](images/jesus_crucifixion_1.png '')
    ![](images/jesus_crucifixion_2.png '')

- ChatGPT can translate code between languages
  - https://twitter.com/rdias002/status/1600019405303611392?s=20&t=7jAbTF0cSLM1H9rt9NCqew
    ![](images/code_translation_1.png '')
    ![](images/code_translation_2.png '')

- Data wrangling and manipulation using ChatGPT
  - https://twitter.com/DataChaz/status/1600135591877742592?s=20&t=FldJBA2NKeurC3LY2JtSIg
    ![](images/data_wrang_1.png '')
    ![](images/data_wrang_2.png '')
    ![](images/data_wrang_3.png '')

- ChatGPT can solve undergrad-level problems on computational complexity
  - https://twitter.com/OfirPress/status/1600434732705415171?s=20&t=g0-mWJ24npbxlXQQ8Loczw
  ![](images/comp_complexity_1.png '')
  ![](images/comp_complexity_2.png '')

- ChatGPT can execute complicated programs if you ask it to print all state updates
  - https://twitter.com/GrantSlatton/status/1600388425651453953?s=20&t=g0-mWJ24npbxlXQQ8Loczw
  ![](images/prog_exec_1.png '')
  ![](images/prog_exec_2.png '')

- Using ChatGPT for generating marketing schemes
  - https://twitter.com/heykahn/status/1599749880515244034?s=20&t=VZfUXFnjm0vVLqwP5VjfeA
  ![](images/seo_strategy.png '')

- ChatGPT as a research assistant working on a new research idea
  - https://twitter.com/SamuelAlbanie/status/1600950546256777216?s=20&t=WG7o3A2teeeDjYOh3kkorQ
  ![](images/research_assistant_1.png '')
  ![](images/research_assistant_2.png '')
  ![](images/research_assistant_3.png '')


## Analysis / Failure Cases

- Analysis of the context window size for ChatGPT (estimated context window size is ~8192)
  - https://twitter.com/goodside/status/1598874674204618753?s=20&t=KMjALYqVD25Ox49ftYtR-Q
    ![](images/context_window_1.png '')
    ![](images/context_window_2.png '')

- ChatGPT explains why abacus is faster than a GPU
  - https://twitter.com/AndrewYNg/status/1600284752258686976?s=20&t=N5wT4zoj_Tw3h4cCrxWT7A
    ![](images/abacus_vs_gpu.png '')

- ChatGPT produces incorrect code implementations -- tested on the development of Snake game using Python
  - https://twitter.com/debarghya_das/status/1600319707545972736?s=20&t=zAi5dfLnTjZABm-pCOe7bw
  ![](images/code_bug_pygame_1.png '')
  ![](images/code_bug_pygame_2.png '')
  ![](images/code_bug_pygame_3.png '')

- Analysis of racism and sexism exhibited by ChatGPT by asking to write code that predicts if someone is senior
  - https://twitter.com/abhi1thakur/status/1600016676052996099?s=20&t=vCy1yu328mi0ae9JCOHaQw
    ![](images/pred_seniority.png '')
  - Successfully reproduced (fails sometimes though)
    ![](images/pred_seniority_reprod.png '')

- Analysis of sexism exhibited by ChatGPT by asking to write code that predicts if someone will be a good scientist
  - https://twitter.com/spiantado/status/1599462375887114240?s=20&t=tPsIN9JugwbB4jj9JgOLuw
    ![](images/pred_good_scientist.png '')
  - Failed to reproduce (might be due to stochasticity)
    ![](images/pred_good_scientist_fail.png '')

- Attempting to pull the cow milk joke on ChatGPT
  - https://twitter.com/PR0GRAMMERHUM0R/status/1599961858039062528?s=20&t=vCy1yu328mi0ae9JCOHaQw
    ![](images/cow_milk_joke.png '')
  - Failed to reproduce
    ![](images/cow_milk_joke_fail.png '')

- ChatGPT makes up content
  - https://twitter.com/Michael_J_Black/status/1598206216525725697?s=20&t=vCy1yu328mi0ae9JCOHaQw

- Showed that ChatGPT can generate sexist and racist lyrics for a song when prompted correctly
  - https://twitter.com/numetaljacket/status/1599540643025793025?s=20&t=vCy1yu328mi0ae9JCOHaQw
    ![](images/racist_rap_good_scientist.png '')
  - Failed to reproduce
    ![](images/racist_rap_good_scientist_fail.png '')

- Attempted to show the mode’s bias by asking it to analyze if someone should be tortured
  - https://twitter.com/janbhwilhelm/status/1599522255775539205?s=20&t=7jAbTF0cSLM1H9rt9NCqew
    ![](images/pred_should_torture.png '')
  - Failed to reproduce
    ![](images/pred_should_torture_fail.png '')

- Ask ChatGPT to write something unintelligible -- writes random sequence of characters
  - https://twitter.com/_andreilupu/status/1603041883680391170?s=20&t=8mNRu2NXQn2oEetAoZ5A5A
    ![](images/write_unintelligible.png '')
  - Successfully reproduced
    ![](images/write_unintelligible_reprod.png '')


## Twitter Threads

- A very recent ChatGPT account posting interesting stuff
    - https://twitter.com/ChatGPTGoneWild

- A list of 15 ChatGPT use-cases
    - https://twitter.com/DataChaz/status/1599754823074598912

- Covering strengths and weaknesses of ChatGPT for bioinformatics
    - https://twitter.com/simocristea/status/1599834929751547905

- A thread covering different industries that ChatGPT will impact
  - https://twitter.com/BrianFOConnor/status/1603032772804857856?s=20&t=DJqk6N4RYvbGQ00-XGtbiQ

- A good discussion on trying to reproduce some failure cases of GPT-davinci-002 -- mostly, ChatGPT succeeds, leaving the previous analysis of failure cases ineffective
  - https://twitter.com/stanislavfort/status/1599417463199830017


## ChatGPT Utilities

- Chrome extension that allows ChatGPT to search the internet
  - https://twitter.com/hahahahohohe/status/1599839969396154369?s=20&t=vCy1yu328mi0ae9JCOHaQw
    <!-- ![](images/search_web_util.png '') -->

- Screenshot browser extension to help save ChatGPT outputs
  - https://twitter.com/Saboo_Shubham_/status/1600035851525918720

- ChatGPT integration for Telegram (also supports Dall-E / Stable Diffusion)
  - https://twitter.com/altryne/status/1598902799625961472?s=20&t=vCy1yu328mi0ae9JCOHaQw
    ![](images/telegram_bot_1.png '')
    ![](images/telegram_bot_2.png '')


## ChatGPT News

- Stack overflow has banned users from posting chatgpt-based generated content
  - https://twitter.com/jjvincent/status/1599743434360639489?s=20&t=vCy1yu328mi0ae9JCOHaQw
  - https://meta.stackoverflow.com/questions/421831/temporary-policy-chatgpt-is-banned


## Missing something?

Please feel free to generate a PR with new and interesting demos that you think we missed.

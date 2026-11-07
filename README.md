# spring-ai-video-description-project
I saw an idea on tik tok about a system that tells you a resume about the content of a video. And I want to make a version with aws. Could be a cool chance to see whats around that dependency.

The idea comes with the following rules as I remember:

-Must proccess multiple videoS at the same time

-Must be cheap

-It must describe the context of a video, a middle-level on specs about content to extract
the must relevant parts of the video.

-It has to take as a context to undersand the video footage and the audio of the video footage,
if there are many characters, according to the relevance of the resume, the project
must be capable of identifying them to add more value to the context of the resume

-We can set for prototype a restriction to take maximum of 2 videos
with a maximum length of five minutes, we don't want to make a full infraestructure
because im not that rich still.

-The resume must be generated in a text file and be saved on some storage (
for prototype's gonna be locally on my machine
)

The idea is to not use much AI for all the heavy work, so we dont burn
too many tokens on the system, not on the work... depending on complexity



# EDIA — A Unity XR Toolbox for research
<video autoplay loop muted playsinline>
    <source src="assets/vid.mp4" type="video/mp4">
    Your browser does not support the video tag.
</video>


EDIA provides you with a set of modules (Unity packages) to facilitate the design and conduction of experimental research in XR using Unity. It is an extension of [UXF — Unity Experiment Framework](https://github.com/immersivecognition/unity-experiment-framework/) (Brookes et al., [2020](https://github.com/immersivecognition/unity-experiment-framework/)).
## Key features

<div class="grid cards" markdown>

-   :simple-instructure:{ .lg .middle } __Structure your experiment__

    ---

    Define the information for your experiment at the granularity level which you need: from sessions to blocks to trials to single steps within trials.

    [:octicons-arrow-right-24: Getting started](https://mind-body-emotion.notion.site/Configs-I-Loading-Trial-and-Block-Settings-1ca03dd4773f8084ae86f153b428a84f)

-   :material-folder-multiple-plus-outline:{ .lg .middle } __Manage it with config files__

    ---

    Use human readable config files to provide and change central information for your experiment without needing to recompile or touch your Unity code.

    [:octicons-arrow-right-24: Overview](https://mind-body-emotion.notion.site/Config-files-1ca03dd4773f80f1b40dd78ae134df26)

-   :material-eye:{ .lg .middle } __Unified eye tracking integration__

    ---

    EDIA provides an integration of eye tracking for multiple different headsets (HTC Vive, Varjo, Meta Quest Pro, Pico 4E), managing the parsing of the eye tracker output for you in the original sampling rate, and providing it via a standardized interface.

    [:octicons-arrow-right-24: EDIA Eye module](#)

-   :material-remote:{ .lg .middle } __Remotely control mobile XR experiments__

    ---

    Control experiments which run on a mobile XR headset (e.g., Meta Quest) externally and stream what the participant is seeing.


    [:octicons-arrow-right-24: EDIA RCAS](#)

-   :fontawesome-regular-pen-to-square:{ .lg .middle } __Automatically log relevant data__

    ---

    Use pre-configured tools to log different kinds of data: behavior and movements of the participant, experimental variables, eye tracking data, ...


    [:octicons-arrow-right-24: Getting started](https://mind-body-emotion.notion.site/Logging-1ca03dd4773f804ab2dafa578397c048)

-   :material-remote:{ .lg .middle } __Synchronize with external data__

    ---

    Use the [LabStreamingLayer protocol](#) to synchronize your experiment with other data streams (e.g., EEG, fNIRS, ...).


    [:octicons-arrow-right-24: EDIA LSL](#)

</div>



## Getting started
Read our [getting started guide](https://mind-body-emotion.notion.site/EDIA-Core-Tutorial-Website-1ca03dd4773f80eb87c9f5f0806f4ece?pvs=74).


### Modules

=== : "EDIA Core"  

    * Structure your experiment.
    * Send messages to the user.
    * Experimenter interface.
    * Use Config files.

=== "EDIA LSL"  

    1. Use LSL to synchronize your data.
    2. Send triggers.
    3. Stream data.

=== "EDIA LSL"  

    1. Sed sagittis eleifend rutrum
    2. Donec vitae suscipit est
    3. Nulla tempor lobortis orci

=== "EDIA RCAS"  

    1. Sed sagittis eleifend rutrum
    2. Donec vitae suscipit est
    3. Nulla tempor lobortis orci

=== "EDIA Eye"  

    1. Sed sagittis eleifend rutrum
    2. Donec vitae suscipit est
    3. Nulla tempor lobortis orci

=== "EDIA LSL"  

    1. Sed sagittis eleifend rutrum
    2. Donec vitae suscipit est
    3. Nulla tempor lobortis orci

=== "EDIA RCAS"  

    1. Sed sagittis eleifend rutrum
    2. Donec vitae suscipit est
    3. Nulla tempor lobortis orci

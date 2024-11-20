# RealAI
RealAI
new addition for details for Real AI

this is about a feature when alarm will be on if timer is greater than 3 seconds

flowchart TD
    A[Start Timer] --> B{Is Timer > 3 seconds?}
    B -- Yes --> C[Activate Alarm]
    B -- No --> D[Continue Timing]
    C --> E[End]
    D --> E

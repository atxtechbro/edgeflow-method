# Idea

## Currently AI is blowing up and getting better every day
    - but we still have a manual dev culture around using it locally
    - applying it locally even with so-called agents we wait for them to finish
    - context switching leads to highly paid engineers essentially babysitting ai, thus relegating us
    - no joy in that

## an automation dev ops approach
    - focuses on dev experience, ergonoics, dev experience and productivity
    - leverages time dev would spend waiting for ai agent to finish locally
    - current cycle of iteration i have seen as a developer using the best ai tools like cursor and others:
        - make change
        - run tests
        - tests fail
        - repeat
    - what if we had a workflow:
        - instead of sequentially going thru those steps
        - an emphasis on the connections between the steps as a whole rather than treating them as indivudual stages or silos
        - naturally appleis systems thinking
        - devs were orchestrating from an elevated and slightly removed view
        - instead of applying, approving, saving, and puishing (monotonous, repetitive, untapped dev potential)
        - a new framework is proposed to elevate the developer to a different stance in the SDLC
        - composing feedback loops to optimize signal from the iteration process
        - product design and thought culture that has a different way of thinking
        - more systems based, less sequential iteration rinse and repeat
        - more testing based, policy driven, dev workflow
        - as much a workflow as any particular aplpication or technology
        - rather than using ai to supplement current dev workflow, it reinvents it
        - yet uses principles and agile dev ops systems thinking and iteration principles that are timeless
    - using these tools
        - cicd focused (agent applies code in cloud without approval, but must pass tests iterated on by developer)
        - while agent is busy working, instead of waiting dev is writing yaml, giving feedback in git commit messages, and this is used for the next iteration in a trace bullet manner
        - critical dev skills still utilized, including git branching and merging skills, communication ability, especially in teams, and writing skills especially
        - agents get feedback from ci cd tests (pass, fail, metadata, logging)
        - devs find it interesting to optimize things like token useage, and making the repo more modular and less token heavy
        - metrics: tokens per query, log lifecycle management (some logs more effective than others in providing useful feedback, and might create noise and more tokens at some point. dev must monitor this, and will enjoy several interesting problem solving challenges)
        - plenty of other challenges sure to emerge, completely unpredictably and organically
        - agents apply their own code in cicd

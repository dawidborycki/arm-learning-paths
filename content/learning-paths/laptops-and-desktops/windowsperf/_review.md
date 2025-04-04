---
# ================================================================================
#       Edit
# ================================================================================

# Always 3 questions. Should try to test the reader's knowledge, and reinforce the key points you want them to remember.
    # question:         A one sentence question
    # answers:          The correct answers (from 2-4 answer options only). Should be surrounded by quotes.
    # correct_answer:   An integer indicating what answer is correct (index starts from 0)
    # explanation:      A short (1-3 sentence) explanation of why the correct answer is correct. Can add additional context if desired


review:
    - questions:
        question: >
            WindowsPerf uses the Arm Performance Monitoring Unit (PMU) counters to generate performance metric reports.
        answers:
            - "True"
            - "False"
        correct_answer: 1
        explanation: >
            The available counters may vary between processors. Use `wperf list` to generate a list of available counters.

    - questions:
        question: >
            Performance metrics are generated per processor.
        answers:
            - "True"
            - "False"
        correct_answer: 1
        explanation: >
            Use `-c` to specify the processor(s) in the system you wish to profile.

    - questions:
        question: >
            WindowsPerf can output data in JSON format with `--json` command line option.
        answers:
            - "True"
            - "False"
        correct_answer: 1
        explanation: >
            Some `wperf` commands such as `list`, `test` or `stat` can output data in JSON format.

    - questions:
        question: >
            Command `wperf sample` can be used together with  `--annotate` or `--disassemble` command line options.
        answers:
            - "True"
            - "False"
        correct_answer: 1
        explanation: >
            Yes, you can add annotate and disassemble output to `wperf sample` command.

    - questions:
        question: >
            Command `wperf record` can be used together with  `--annotate` or `--disassemble` command line options.
        answers:
            - "True"
            - "False"
        correct_answer: 1
        explanation: >
            Yes, you can add annotate and disassemble output to `wperf record` command.


# ================================================================================
#       FIXED, DO NOT MODIFY
# ================================================================================
title: "Review"                 # Always the same title
weight: 20                      # Set to always be larger than the content in this path
layout: "learningpathall"       # All files under learning paths have this same wrapper
---

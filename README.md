## Folder Structure
Folder             | Description
-------------------| -----------------------------------------
`1_Requirements`   | Documents detailing requirements and research
`2_Design`         | Documents specifying design details
`3_Implementation` | All code and documentation
`4_Test_plan`      | Documents with test plans and procedures

## Contributors List and Summary

SF No. |  Name   |    Features    | Issuess Raised |Issues Resolved|No Test Cases|Test Case Pass
-------|---------|----------------|----------------|---------------|-------------|--------------
`256153` | S Sanchana  | Metric Conversion    | Nil     | Nil   |9   | YES    
   

## Challenges Faced and How Was It Overcome

1. Inputing char for int in while(1) loop lead to infinite loop -> got value as fgets
2. Including files -> later resolved

## Project Enhancements carried out
Variable | Bug | Fix
--- | --- | ----
input_value | Character inputs was considered 0 | Indicated as invalid and user asked to re-enter
input_value | Negative inputs were accepted by considering their absolute values | Indicating metric cannot be negative, user asked to re-enter
choice_of_quantity, index_of_input, number_of_output_conversions, array_of_output_index[i] | fseek to flush stdin, so next variable does not take values from previous input was not working in linux | Buffer size increased to fit accidental extra values
choice_of_quantity, index_of_input, number_of_output_conversions, array_of_output_index[i] | only 1st digit was considered for index, thus, accidental 123 input is considered index 1 | Fixed by prompting user to re-enter input within the range

### Miscellaneous
* Inclusion of appropriate comments
* YML for windows created
* doxyfile generated
* codacy badge included

## Learning Resources
1. [markdownCheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
2. [markdownBasics](https://guides.github.com/features/mastering-markdown/)
3. [git inspector](https://github.com/ejwa/gitinspector.git)
4. [github workflow](https://docs.github.com/en/actions/learn-github-action)

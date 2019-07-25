# cool react app with 6 Templates
## Team Members
** Jen, William F, Anthony**

## Errors
+ Template 1 error:
  + ‘cool-react-bucket’ should have been ‘coolReactBucket’.
  ![](.images/aws1err1.png)

  + Website works as expected
+ Template 2 error:
  + No bugs when uploading yml but website not working -> found that maybe gitHub OAuth has to be different each time, because we updated with template one and website would still not work
  ![](.images/aws2pageErr1.png)
+ Template 3 error:
  + ‘cool’ was missing in ‘cool-react-app’.
  + website does not work -> forbidden
+ Template 4 error:
  + CodePipeLine was not correctly camel cased.
  + It was also missing a the codebuildrole section of the Yml file.
  ![](.images/aws4err1.png)
  ![](.images/aws4err2.png)
  ![](.images/aws4stackerr1.png)

  + Stack fails
+ Template 5 error:
  + There was a missing ‘!’ in front of one the joins.
  + Stack fails
  ![](.images/stack5err.png)


+ Template 6 error:
  + ‘cool-react-bucket.’ should have been ‘coolReactBucket’.
  + One of the codepipelines was spelled wrong.
  + "recursive" missing in post-build
  ![](.images/aws6err1.png)
  ![](.images/aws6err2.png)

  + stack fails
  ![](.images/aws6stackerr1.png)

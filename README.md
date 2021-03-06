# draft-ietf-kitten-password-storage
Best practices for password hashing and storage
([datatracker](https://datatracker.ietf.org/doc/draft-ietf-kitten-password-storage/))

This is tracking a document of the [IETF kitten Working
Group](https://datatracker.ietf.org/wg/kitten), and is subject to the
provisions of the IETF. NOTE WELL: https://www.ietf.org/about/note-well.html
and see also the CONTRIBUTING.md file.

Feel free to make pull requests against this README.md if you have made a
review and would like it added.

draft-ietf-kitten-password-storage was first published as a kitten document on 2020-06-20.

| Reviewer        | Review Date | Version Reviewed | Review Notes/Summary                                                                | Link to Review                                                            |
|-----------------|-------------|------------------|-------------------------------------------------------------------------------------|---------------------------------------------------------------------------|
| Simon Josefsson | 2020-04-28  | whited-00        | minor, sorting criteria, use of PLAIN                                               | https://mailarchive.ietf.org/arch/msg/kitten/t8Yms70uBrbL-F_LP4Olim4WJrE/ |
| Jim Fenton      | 2020-09-04  | -00              | terminology clarifications, salt+pepper size and storage, handling common passwords | https://mailarchive.ietf.org/arch/msg/kitten/X6ltZh0F3QcKAjc3lumN7cAo3Kc/ |
| Ludovic Bocquet | 2020-10-29  | -00              | SCRAM-related changes including ordering                                            | https://mailarchive.ietf.org/arch/msg/kitten/ek52im03XXz0y4TmY4C9sxDospk/ |
| Steve Thomas    | 2020-10-30  | -01              | hash speeds, work factors                                                           | https://mailarchive.ietf.org/arch/msg/kitten/jJdxBQUcmJBcYK7J4HlTJEH1MPg/ |
| Alexey Melnikov | 2020-11-03  | -01              | elaboration on salts with SCRAM, origin of minimum iteration count                  | https://mailarchive.ietf.org/arch/msg/kitten/bqenAMNnhzq1bkoi3rfA3tahnVk/ |
| Steve Thomas    | 2020-11-22  | -02              | scrypt details, hashing output length                                               | https://mailarchive.ietf.org/arch/msg/kitten/W3BRxHm1rlGlqeHG1jShioyHVMQ/ |
| Steve Thomas    | 2021-03-11  | -03              | hashing output length (same as previous review)                                     | https://mailarchive.ietf.org/arch/msg/kitten/_uBIC733w2jhfFTryXHrkmZ6HEs/ |
| Jim Fenton      | 2021-03-20  | -04              | secrets, efinitions, OWASP                                                          | https://mailarchive.ietf.org/arch/msg/kitten/M8LHRT9tBJ46zl3cXIqfrfQJ-hE/ |

# G54FPP coursework
* Grade: 74 / 100
* Repository: [link](https://github.com/SpeedoDevo/heapsort.agda)
* Comments:
>Your Agda development is not complete since you have not shown that the implemented sorting function is correct, and disabling the termination checker in Sort/Sort.agda is of course not a satisfactory solution (this termination is a critical point, I think we had discussed this in Venanzio's office). Still, taking into account that you had to teach Agda to yourself before you could even get started, your implementation is very good. Your report is short and precise. I don't see it as a minus that you didn't have slides for your presentation; there is absolutely nothing wrong with whiteboard presentations. (Caveat: Other people could judge this differently.) I have enjoyed your presentation, you were a confident and competent speaker and able to answer questions. Well done.Small remark regarding the Agda code: in most basic examples, you don't need to use equality in constructors of inductive families. E.g. there's no reason to write
>```agda
>   leafIsLeftist : {t : HTree} -> t ≡ leaf -> t IsLeftist
>```
>better write
>```agda
>   leafIsLeftist : leaf IsLeftist
>```
>This will make things a bit shorter.

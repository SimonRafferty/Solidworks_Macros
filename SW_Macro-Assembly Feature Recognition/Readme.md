This macro is the same as automatic feature recognition which you can run from within SW, except it will work on an assembly.

It's not perfect - and is rather slow.  However it has proven useful, in particular for converting an assembly from a future version of SW (exported as STEP or Parasolid) into a previous one, converting it into a fully editable part.

Unfortunately, it looses all the assembly level mates, just leaving the parts locked into place.  However, if you run 'SW-Macro - Add Mates' on the result, it will at least make a start on re-rigging the assembly.

It will still need some 'fixing' but it can save a heap of time.

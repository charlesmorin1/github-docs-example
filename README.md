# Writing Good Documentation

## Step 1 - Using Codeblocks.

Codeblocks in markdown make it *very easy* for tech people to **copy, paste, share code**. A good Cloud Engineer uses Codeblocks whenever possible.

Because it allows others to copy and paste their code to replicate or research issues.

```
def find_missing(sequence)
  consecutive = sequence.each_cons(2)
  missing_between = consecutive.find { |a, b| (b - a) != sequence }
  missing_between.first + sequence
end

find_missing([2, 4, 6, 10]) # Output: 8

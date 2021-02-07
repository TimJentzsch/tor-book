# Code

Subreddits like r/badcode or r/ProgrammerHumor often contain screenshots of code.

There are two ways to format code in Reddit: Using fenced (` ``` `) or indented (` `) codeblocks.
Please always use the indented codeblocks, as fenced codeblocks are not supported on all Reddit clients.

<div class="reddit-preview-container">
<div class="reddit-preview">

```markdown
*Image Transcription: Code*

---

    # Python program for implementation of Bubble Sort 
      
    def bubbleSort(arr): 
        n = len(arr) 
      
        # Traverse through all array elements 
        for i in range(n-1): 
        # range(n) also work but outer loop will repeat one time more than needed. 
      
            # Last i elements are already in place 
            for j in range(0, n-i-1): 
      
                # traverse the array from 0 to n-i-1 
                # Swap if the element found is greater 
                # than the next element 
                if arr[j] > arr[j+1] : 
                    arr[j], arr[j+1] = arr[j+1], arr[j] 
      
    # Driver code to test above 
    arr = [64, 34, 25, 12, 22, 11, 90] 
      
    bubbleSort(arr) 
      
    print ("Sorted array is:") 
    for i in range(len(arr)): 
        print ("%d" %arr[i]),  

---

I'm&#32;a&#32;human&#32;volunteer&#32;content&#32;transcriber&#32;for&#32;Reddit&#32;and&#32;you&#32;could&#32;be&#32;too!&#32;[If&#32;you'd&#32;like&#32;more&#32;information&#32;on&#32;what&#32;we&#32;do&#32;and&#32;why&#32;we&#32;do&#32;it,&#32;click&#32;here!](https://www.reddit.com/r/TranscribersOfReddit/wiki/index)
```

</div>
<div class="reddit-preview">

*Image Transcription: Code*

---


    # Python program for implementation of Bubble Sort 
      
    def bubbleSort(arr): 
        n = len(arr) 
      
        # Traverse through all array elements 
        for i in range(n-1): 
        # range(n) also work but outer loop will repeat one time more than needed. 
      
            # Last i elements are already in place 
            for j in range(0, n-i-1): 
      
                # traverse the array from 0 to n-i-1 
                # Swap if the element found is greater 
                # than the next element 
                if arr[j] > arr[j+1] : 
                    arr[j], arr[j+1] = arr[j+1], arr[j] 
      
    # Driver code to test above 
    arr = [64, 34, 25, 12, 22, 11, 90] 
      
    bubbleSort(arr) 
      
    print ("Sorted array is:") 
    for i in range(len(arr)): 
        print ("%d" %arr[i]),

---

<sup>I'm&#32;a&#32;human&#32;volunteer&#32;content&#32;transcriber&#32;for&#32;Reddit&#32;and&#32;you&#32;could&#32;be&#32;too!&#32;[If&#32;you'd&#32;like&#32;more&#32;information&#32;on&#32;what&#32;we&#32;do&#32;and&#32;why&#32;we&#32;do&#32;it,&#32;click&#32;here!](https://www.reddit.com/r/TranscribersOfReddit/wiki/index)</sup>

</div>
</div>

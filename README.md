# Vi_Cheatsheet (Works for Vi && Vim)


## Basic Usage

1. To open a file/create a new file using vi:
   ```
   vi FILE_NAME.c
   ```

1. To switch to `EDIT MODE`, press `ESC`.

1. To switch to `INSERT MODE`, press `i`.

1. To save a file, go to `EDIT MODE` and write:
   ```
   :w
   ```

1. To save a file and exit, go to `EDIT MODE` and use either of these:
   ```
   :x 
   ```

   ```
   SHIFT ZZ
   ```

1. To exit without making any changes, go to `EDIT MODE` and enter:
   ```
   :q
   ```

1. To exit without saving, go to `EDIT MODE` and write:
   ```
   :q!
   ```

1. To display number lines, go to `EDIT MODE` and write:
   ```
   :set nu 
   ```


## Movement Controls (All in EDIT MODE)

1. Move left one character --> `h`.

2. Move down one character --> `j`.

3. Move up one character --> `k`.

4. Move right one character --> `l`.

5. Move forward one word --> `w`.

6. Move to the start of the word --> `b`.

7. Move to the end of the word --> `e`.

8. Move back one sentence --> `(`.

9. Move forward one sentence --> `)`.

10. Move back one paragraph --> `{`.

11. Move forward one paragraph --> `}`.

12. Move to the beginning of the line --> `^`.

13. Move to the end of the line --> `$`.

14. Move to the nth line --> `<n>G`.

15. Move to the last line --> `G`.

16. Move to the first line --> `gg`.

17. Move to the matching bracket --> `%`.


## INSERT MODE Controls

1. At the cursor --> `i`.

2. After the cursor --> `a`.

3. Before the current line --> `I`.

4. After the current line --> `A`.

5. Insert a new line after the current line --> `o`.

6. Insert a new line before the current line --> `O`.

7. Ovewrite the whold current line --> `C`.

8. Exit Insert mode --> `ESC`.


## Deleting Text Controls (All in EDIT MODE)

1. Delete a single character --> `x`.

2. Delete the rest of the line --> `D`.

3. Delete the entire current line --> `dd`.

4. Delete the next n words --> `ndw`.

5. Delete the next n lines --> `ndd`.

6. Delete from line x through to line y --> `:x,yd`.


## Cut and Paste Controls (All in EDIT MODE)

1. Paste the clipboard contents --> `p`.

2. Yank (copy) a line --> `yy`.

3. Yank a word --> `yw`.

4. Yank to the end of the line --> `y$`.


## Search Controls (All in EDIT MODE)

1. Search for pattern --> `/pattern`.

2. Find the next occurrence of pattern (after using the previous command) --> `n`.

3. Replace every occurrence of "pattern" with "replace" --> `:%s/pattern/replace/g`.

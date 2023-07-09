# Frida Fadeeva

## Contact Information
- Email: frida.fadeeva@gmail.com

## Skills
- Programming Languages: C
- Tools: Git, Make
- Operating Systems: Linux, macOS
- Problem Solving
- Attention to Detail
- Teamwork and Collaboration

## Projects
- **Cat Project**
  - Description: Developed a command-line utility similar to the `cat` command in Unix, which concatenates and displays the contents of files. Implemented error handling, file I/O, and command-line argument parsing.
  - Technologies: C

- **Grep Project**
  - Description: Created a simplified version of the `grep` command in Unix, which searches for specified patterns in text files. Implemented pattern matching, file handling, and output formatting.
  - Technologies: C
  - Code Snippet:

```c
void f_flag(char* optarg, int e_count, char* ef_flags) {
    FILE* fp_f = NULL;
    
    if ((fp_f = fopen(optarg, "r")) == NULL) {
        printf("grep: %s: No such file or directory\n", optarg);
    } else {
        char line[BUFFER] = {0};
        
        while (fgets(line, BUFFER, fp_f) != NULL) {
            strtok(ef_flags, "\n");
            if (e_count != 0) strcat(ef_flags, "|");
            strcat(ef_flags, line);
        }
        
        fclose(fp_f);
    }
}
```

## Education
- School21
- Specialization: Software Development
- Relevant Courses: Algorithms, Data Structures, Computer Architecture

## Personal Projects
- **File Compression Tool**
  - Description: Developed a file compression tool using C, implementing a lossless compression algorithm. Experimented with different data compression techniques and optimized the algorithm for performance.
  - Technologies: C

## Languages
- Native: Russian
- Fluent: English

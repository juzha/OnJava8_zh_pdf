# OnJava8_zh_pdf

文件 《On-Java-8_Zh.pdf》 中的内容来自这个项目： https://github.com/LingCoder/OnJava8

这个地址是本书中的实例代码仓库： https://github.com/BruceEckel/OnJava8-Examples

原仓库中文件是每一章节一个 md 文件，[pandoc](https://github.com/jgm/pandoc) 和  [TinyTeX](https://yihui.org/tinytex/) 在 Windows下整理成独立pdf

保持更新， 保持准确的书签

pandoc -s -o "C:\Users\juzha\GitHub\OnJava8\docs\book\pdf\final.pdf" --pdf-engine=xelatex -V mainfont="PingFang SC" --template=template.tex 00-Preface.md 00-Introduction.md 01-What-is-an-Object.md 02-Installing-Java-and-the-Book-Examples.md 03-Objects-Everywhere.md 04-Operators.md 05-Control-Flow.md 06-Housekeeping.md 07-Implementation-Hiding.md 08-Reuse.md 09-Polymorphism.md 10-Interfaces.md 11-Inner-Classes.md 12-Collections.md 13-Functional-Programming.md 14-Streams.md 15-Exceptions.md 16-Validating-Your-Code.md 17-Files.md 18-Strings.md 19-Type-Information.md 20-Generics.md 21-Arrays.md 22-Enumerations.md 23-Annotations.md 24-Concurrent-Programming.md 25-Patterns.md Appendix-Supplements.md Appendix-Programming-Guidelines.md Appendix-Javadoc.md Appendix-Passing-and-Returning-Objects.md Appendix-IO-Streams.md Appendix-Standard-IO.md Appendix-New-IO.md Appendix-Understanding-equals-and-hashCode.md Appendix-Collection-Topics.md Appendix-Low-Level-Concurrency.md Appendix-Data-Compression.md Appendix-Object-Serialization.md Appendix-Benefits-and-Costs-of-Static-Type-Checking.md Appendix-The-Positive-Legacy-of-C-plus-plus-and-Java.md Appendix-Becoming-a-Programmer.md GLOSSARY.md
- 👋 Hi, I’m @akashjod1
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
akashjod1/akashjod1 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
root = true

[*]
tab_width = 2
indent_size = 2
charset = utf-8
end_of_line = lf
indent_style = space
insert_final_newline = true
trim_trailing_whitespace = true

[*.txt]
indent_size = false

[test/fast/Listing versions/Running 'nvm ls' calls into nvm_alias]
indent_size = false

[test/fast/Listing versions/Running 'nvm ls --no-alias' does not call into nvm_alias]
indent_size = false

[test/fast/Unit tests/mocks/**]
insert_final_newline = off

[test/**/.urchin*]
insert_final_newline = off

[Makefile]
indent_style = tab

[test/fixtures/nvmrc/**]
indent_style = off
insert_final_newline = off

[test/fixtures/actual/alias/empty]
insert_final_newline = off

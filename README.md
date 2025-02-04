- 👋 Hi, I’m @postnext
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
postnext/postnext is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
conditions  []ifCondition
}
// ifCondition can match a WebDAV resource, based on a stateToken or ETag.
// Exactly one of stateToken and entityTag should be non-empty.
type ifCondition struct {
	not        bool
	stateToken string
	entityTag  string

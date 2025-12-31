# GitHub Foundations — Domain 2: Working with GitHub Repositories  
## PART 1 (Q1–63) — Questions with One-Line Answers

---

1. What are the key components of a good README on GitHub?  
**Answer:** Project overview, installation, usage, contribution guidelines, and license.

2. Why is a README typically the first file a visitor should read?  
**Answer:** It explains what the project is and how to use it.

3. Where does GitHub commonly display the README in a repository?  
**Answer:** On the repository home page below the file list.

4. What is the difference between README content and repository description?  
**Answer:** README is detailed documentation, while description is a short summary.

5. Which README format is most commonly used on GitHub?  
**Answer:** README.md (Markdown).

6. What are typical sections found in a strong README?  
**Answer:** Overview, installation, usage, contributing, and license.

7. What is the purpose of an “Installation” section in README?  
**Answer:** To explain how to set up the project locally.

8. What is the purpose of a “Usage” section in README?  
**Answer:** To show how to run or use the project.

9. What is the purpose of a “Contributing” section in README?  
**Answer:** To guide others on how to contribute properly.

10. What is the purpose of a “License” section in README?  
**Answer:** To clarify legal usage rights of the project.

11. Why are badges included in a README?  
**Answer:** To show project status like build, coverage, or license.

12. What is the difference between project overview and technical documentation?  
**Answer:** Overview explains the idea; technical docs explain implementation.

13. When should you include a “Prerequisites” section in README?  
**Answer:** When the project requires specific tools or dependencies.

14. What content should be avoided in a README for security reasons?  
**Answer:** Secrets, passwords, or API keys.

15. What is the purpose of a LICENSE file?  
**Answer:** It defines how others can legally use the code.

16. What does a LICENSE file help contributors understand?  
**Answer:** Their rights and restrictions when using the code.

17. What happens if a repository has no LICENSE file?  
**Answer:** The code is legally protected and cannot be reused freely.

18. Why do open-source projects include a LICENSE?  
**Answer:** To clearly allow reuse under defined terms.

19. What is the purpose of a CONTRIBUTING file?  
**Answer:** To explain how others should contribute to the project.

20. Where is the CONTRIBUTING file usually placed?  
**Answer:** In the root or `.github` directory.

21. What is a CODEOWNERS file used for?  
**Answer:** To assign reviewers to specific files or paths.

22. How does CODEOWNERS affect pull requests?  
**Answer:** It automatically requests reviews from owners.

23. Who typically manages the CODEOWNERS file?  
**Answer:** Repository maintainers or admins.

24. Where can CODEOWNERS be located?  
**Answer:** Root, `.github/`, or `docs/` directory.

25. What is the difference between recommended and required repo files?  
**Answer:** Recommended files improve collaboration but are not mandatory.

---

26. What is repository navigation on GitHub?  
**Answer:** Browsing files, folders, branches, and commits.

27. What does the “Code” tab show?  
**Answer:** The repository file structure and contents.

28. What does the file tree represent?  
**Answer:** The folder and file hierarchy of the repository.

29. What is breadcrumb navigation used for?  
**Answer:** To track and move through folder paths.

30. How do you switch branches using GitHub UI?  
**Answer:** Using the branch dropdown menu.

31. How do you view a file’s contents on GitHub?  
**Answer:** By clicking the file name.

32. How do you view a file’s revision history?  
**Answer:** Using the “History” button for the file.

33. What is the “History” feature used for?  
**Answer:** To see all past changes to a file or folder.

34. How do you search within a repository?  
**Answer:** Using the search bar scoped to the repo.

35. What is the “Go to file” feature used for?  
**Answer:** To quickly locate a file by name.

36. How do you download a repository without cloning?  
**Answer:** Using “Download ZIP”.

37. What is the difference between Download ZIP and clone?  
**Answer:** ZIP has no history; clone includes full history.

38. What does the README area help users with?  
**Answer:** Understanding the project quickly.

39. Where are key project links usually displayed?  
**Answer:** In the repository “About” section.

40. What is the purpose of the repository “About” section?  
**Answer:** To summarize and link project resources.

41. What are repository topics used for?  
**Answer:** Categorizing and improving discoverability.

42. How do topics improve discoverability?  
**Answer:** They help users find related projects.

43. What is the difference between repo name and URL slug?  
**Answer:** Name is display text; slug is URL-friendly.

44. What is the default branch?  
**Answer:** The main branch where stable code lives.

45. How can you identify the default branch in UI?  
**Answer:** It is labeled in the branch selector.

---

46. How do you create a new repository on GitHub?  
**Answer:** By using the “New repository” option.

47. What is the minimum required field to create a repo?  
**Answer:** Repository name.

48. What is the difference between personal and org repos?  
**Answer:** Ownership and access control.

49. What is repository visibility?  
**Answer:** Who can see the repository.

50. When should you choose a public repository?  
**Answer:** When the project is open for everyone.

51. When should you choose a private repository?  
**Answer:** When access must be restricted.

52. What does internal repository visibility mean?  
**Answer:** Visible only within an organization.

53. Why initialize a repository with a README?  
**Answer:** To provide immediate documentation.

54. What is a .gitignore file used for?  
**Answer:** To exclude files from version control.

55. When should you add a LICENSE during repo creation?  
**Answer:** When you want to allow code reuse.

56. How do you choose a license?  
**Answer:** Based on how you want others to use your code.

57. What is the repository description used for?  
**Answer:** To briefly explain the project.

58. What is the repository homepage URL field for?  
**Answer:** To link an external project website.

59. What happens after creating a repo with no files?  
**Answer:** The repository is empty until files are added.

60. How do you add your first file via GitHub UI?  
**Answer:** Using “Add file” → “Create new file”.

61. What is the benefit of adding a README first?  
**Answer:** It makes the repo understandable immediately.

62. What is the benefit of adding .gitignore early?  
**Answer:** Prevents unwanted files from being tracked.

# GitHub Foundations — Domain 2: Working with GitHub Repositories  
## PART 2 (Q64–126) — Questions with One-Line Answers

---

64. What is a repository template?  
**Answer:** A pre-configured repository used to create new repos with the same starting files/structure.

65. What problem do templates solve for teams?  
**Answer:** They standardize setup and reduce repetitive boilerplate work.

66. How is a template repository different from a fork?  
**Answer:** Templates copy files without history; forks copy the repo with history and linkage.

67. Does creating from a template copy commit history?  
**Answer:** No, it creates a new repo without the original commit history.

68. What content is copied from a template repository?  
**Answer:** Repository files and directory structure (not history).

69. Who can mark a repository as a template?  
**Answer:** Users with admin/owner permissions on the repository.

70. What types of projects benefit most from template repos?  
**Answer:** Repetitive projects like services, libraries, or standard internal apps.

71. What is a “starter template” use case in organizations?  
**Answer:** Providing a consistent baseline for new team repositories.

72. What is a “scaffold” use case for templates?  
**Answer:** Bootstrapping a project with folders, configs, and docs.

73. What repo standards can templates enforce?  
**Answer:** Standard README, LICENSE, CI configs, and folder structure.

74. How can templates help maintain consistent licensing?  
**Answer:** They include the correct LICENSE file by default.

75. How can templates help enforce consistent CI setup?  
**Answer:** They ship pre-made workflows/config files for automation.

76. What is the difference between a template repo and cloning?  
**Answer:** Templates create a new repo; cloning creates a local copy of the same repo.

77. What happens if a template repo is updated after you created a repo from it?  
**Answer:** Your created repo does not automatically update.

78. What does “Use this template” do in GitHub UI?  
**Answer:** It generates a new repository from a template repository.

79. When should you avoid using templates?  
**Answer:** When the project needs a unique structure not shared by others.

80. How do templates improve onboarding?  
**Answer:** New projects start with familiar standards and documentation.

---

81. What does it mean to “maintain a repository”?  
**Answer:** Keeping it organized, updated, secure, and easy to collaborate on.

82. What are examples of repository housekeeping tasks?  
**Answer:** Updating docs, cleaning files, managing branches, and organizing structure.

83. Why is keeping the README updated part of maintenance?  
**Answer:** It prevents confusion and reduces onboarding/support effort.

84. Why are dependency updates considered maintenance?  
**Answer:** They reduce security risks and improve stability.

85. How do labels and templates support maintainability?  
**Answer:** They standardize triage and reduce issue noise.

86. How does a clean folder structure help maintainability?  
**Answer:** It makes files easier to find and understand.

87. Why should you never commit secrets into a repository?  
**Answer:** They can leak and be abused, even if removed later.

88. What is a recommended approach for handling sensitive data?  
**Answer:** Use secret managers and environment variables instead of committing secrets.

89. How can you reduce repository clutter over time?  
**Answer:** Remove unused files, close stale items, and delete merged branches.

90. Why do teams enforce coding standards in repositories?  
**Answer:** To keep code consistent and easier to review/maintain.

91. How can CODEOWNERS support maintainability?  
**Answer:** It routes changes to the right reviewers automatically.

92. How do branch protections support maintenance (high level)?  
**Answer:** They prevent unsafe direct changes to important branches.

93. Why is documentation maintenance important?  
**Answer:** Accurate docs reduce mistakes and speed up work.

94. How do releases/tags relate to maintainability (high level)?  
**Answer:** They provide stable reference points for versions.

95. What is repository archiving and when is it used?  
**Answer:** Making a repo read-only when it’s no longer actively maintained.

---

96. What does it mean to clone a repository?  
**Answer:** Creating a full local copy including commit history.

97. What gets copied during a clone?  
**Answer:** Repository files plus the full Git history.

98. What is the difference between cloning and forking?  
**Answer:** Clone is local copy; fork is a GitHub copy under your account.

99. When would you fork instead of clone?  
**Answer:** When you want to contribute without write access to the original repo.

100. What is the difference between cloning via HTTPS vs SSH (conceptually)?  
**Answer:** HTTPS uses credentials/tokens; SSH uses SSH keys.

101. What is the role of authentication when cloning private repos?  
**Answer:** It proves permission to access the private repository.

102. What does “origin” typically refer to after cloning?  
**Answer:** The default remote pointing to the source repository.

103. What is a remote URL in the context of cloning?  
**Answer:** The address Git uses to fetch/push to the remote repository.

104. What is a local working copy and why is it useful?  
**Answer:** It lets you edit and commit changes locally.

105. What is the relationship between local commits and pushing to GitHub?  
**Answer:** Commits are local until you push them to a remote.

106. What is a shallow clone (conceptually) and why use it?  
**Answer:** A clone with limited history to save time and space.

107. What is the difference between cloning and downloading ZIP for collaboration?  
**Answer:** Cloning supports commits/push/pull; ZIP is just files without Git history.

108. What is a typical first step after cloning locally?  
**Answer:** Create a branch and begin making changes.

109. Why might cloning fail for a private repository?  
**Answer:** Because you don’t have access or proper authentication.

110. How can you verify a successful clone?  
**Answer:** The repo folder exists locally and `git status` works inside it.

---

111. How do you create a new branch (conceptually)?  
**Answer:** Create a new line of development from an existing commit.

112. Why create new branches before making changes?  
**Answer:** To isolate work and protect the default branch.

113. What is a feature branch?  
**Answer:** A branch created to develop a specific feature or change.

114. What is the default branch used for in most workflows?  
**Answer:** Holding stable, reviewed code.

115. Why is clear branch naming important?  
**Answer:** It makes purpose and ownership obvious for collaboration.

116. What is the difference between creating a branch locally vs in GitHub UI?  
**Answer:** Local uses Git commands; UI creates the branch directly on GitHub.

117. What does it mean to “publish” a branch to GitHub?  
**Answer:** Push the local branch to the remote repository.

118. What is the relationship between branches and pull requests?  
**Answer:** PRs propose merging a branch into another branch.

119. How do branches help reduce collaboration risk?  
**Answer:** They prevent unreviewed changes from affecting the default branch.

120. What is a branch pointer (conceptually)?  
**Answer:** A reference that points to a commit in history.

121. What happens when you create a branch from the latest commit on main?  
**Answer:** Your branch starts with the newest code from main.

122. What are common beginner mistakes with branches?  
**Answer:** Working directly on main or forgetting to sync with default branch.

123. When should a branch be deleted?  
**Answer:** After it’s merged and no longer needed.

124. What is a remote-tracking branch (conceptually)?  
**Answer:** A local reference to the state of a remote branch.

125. What does it mean for your branch to be “behind” default branch?  
**Answer:** Default branch has commits your branch doesn’t include.

126. What does it mean for your branch to be “ahead” of default branch?  
**Answer:** Your branch has commits not yet merged into default branch.

# GitHub Foundations — Domain 2: Working with GitHub Repositories  
## PART 3 (Q127–189) — Questions with One-Line Answers

127. How do you add files to a repository using the GitHub web UI?  
**Answer:** Use “Add file” then “Upload files” or “Create new file.”

128. How do you upload multiple files to a repo via UI?  
**Answer:** Select multiple files in “Upload files” dialog.

129. How do you create a new file directly in the GitHub UI?  
**Answer:** Click “Add file” → “Create new file.”

130. What is the role of commit messages when adding files via UI?  
**Answer:** To describe what changes are being added.

131. What does GitHub ask you when you commit changes via UI?  
**Answer:** Which branch to commit the changes to.

132. Why should you avoid committing large binaries to a repository?  
**Answer:** They bloat the repo and slow down performance.

133. What file types are typically stored in repos vs elsewhere?  
**Answer:** Source, docs, configs in repos; generated assets elsewhere.

134. What is the purpose of .gitignore when adding files?  
**Answer:** To exclude files from being tracked by Git.

135. What happens if you add files directly to the default branch?  
**Answer:** The changes immediately affect the main codebase.

136. Why is it safer to add files on a new branch?  
**Answer:** It isolates changes until reviewed.

137. What is the difference between editing and uploading a file?  
**Answer:** Editing changes existing content; uploading adds new files.

138. What is the “Edit” pencil icon on GitHub?  
**Answer:** It opens a file in edit mode in UI.

139. What is the “Preview” tab used for when editing Markdown?  
**Answer:** To see how rendered content looks.

140. How do you rename a file via GitHub UI?  
**Answer:** Edit the filename inline then commit.

141. How do you delete a file via GitHub UI?  
**Answer:** Use the trash/delete icon then commit the removal.

142. What is the difference between deleting a file and removing it from history?  
**Answer:** Delete hides it going forward; history still contains it.

143. What is the impact of committing directly to a protected branch?  
**Answer:** It’s disallowed or blocked by policy.

144. How do you revert a change if you committed the wrong file?  
**Answer:** Use revert or undo changes manually.

145. What is a commit diff and how does it help verify file additions?  
**Answer:** It shows changes line by line for review.

146. Why should you review changes before committing via UI?  
**Answer:** To avoid mistakes or unintended edits.

147. What are repository insights on GitHub?  
**Answer:** Analytics about traffic, contributions, and activity.

148. What kinds of information are typically in Insights?  
**Answer:** Traffic, commits, code frequency, contributors.

149. What is “Traffic” in repository insights?  
**Answer:** Views, clones, and referrers data.

150. What does “Views” in traffic represent?  
**Answer:** Number of times the repo was viewed.

151. What do “Unique visitors” represent?  
**Answer:** Distinct users who viewed the repo.

152. What does “Clones” represent in traffic?  
**Answer:** Times the repo was cloned locally.

153. Over what time window does GitHub traffic show data?  
**Answer:** Typically last 14 days.

154. What are “Referring sites” in traffic insights?  
**Answer:** Websites leading users to the repo.

155. What is “Popular content” in traffic insights?  
**Answer:** Most viewed pages/files.

156. Why might traffic insights be useful to maintainers?  
**Answer:** To understand interest and improve docs.

157. Who can view repository traffic (in general)?  
**Answer:** Users with permission (owners/collaborators).

158. What is the “Contributors” insight?  
**Answer:** A summary of contributors and their commit counts.

159. What does a contributor graph typically show?  
**Answer:** Who contributed and how much.

160. What is “Commits” insight used for?  
**Answer:** To see historical commit patterns.

161. What is “Code frequency” insight?  
**Answer:** Visualization of code additions/deletions over time.

162. What is “Pulse” insight used for?  
**Answer:** Snapshot of recent activity and health.

163. How can insights help understand repository health?  
**Answer:** They show activity, growth, and usage trends.

164. What does it mean to star a repository?  
**Answer:** Show interest/bookmark the project.

165. Why do developers star repositories?  
**Answer:** To bookmark projects they like.

166. Does starring a repository automatically give you notifications?  
**Answer:** No, starring does not subscribe to notifications.

167. What is the difference between starring and watching?  
**Answer:** Watching subscribes to activity notifications; starring just bookmarks.

168. Where do you find your starred repos on GitHub?  
**Answer:** Under your profile “Stars” tab.

169. How do stars help repository discoverability?  
**Answer:** Higher stars can boost visibility.

170. How can maintainers interpret stars?  
**Answer:** As popularity or interest indicators.

171. Can you unstar a repository and what happens?  
**Answer:** Yes, it removes the bookmark.

172. What is the difference between starring and forking?  
**Answer:** Forking creates a copy; starring just bookmarks.

173. What is the difference between starring and bookmarking a URL?  
**Answer:** Star shows on GitHub profile; bookmarks are browser-only.

174. When might a company encourage employees to star internal repos?  
**Answer:** To indicate important internal resources.

175. How do stars relate to “social proof” on GitHub?  
**Answer:** More stars signal higher community endorsement.

176. What are feature previews in GitHub?  
**Answer:** Early access experimental features.

177. Why does GitHub offer feature previews?  
**Answer:** To test and refine features before full release.

178. Where can you enable feature previews (conceptually)?  
**Answer:** In account or org feature settings.

179. What is the risk of using preview features in production?  
**Answer:** They may change or be removed later.

180. How can feature previews affect repo behavior (conceptually)?  
**Answer:** They may alter UI or functionality temporarily.

181. Can feature previews be organization-wide conceptually?  
**Answer:** Yes, enabled at org level for teams.

182. Why might a team enable a preview feature temporarily?  
**Answer:** To test improvements or new workflows.

183. What should you do if a preview feature is removed?  
**Answer:** Update workflow according to final feature behavior.

184. What is the purpose of repository settings (high level)?  
**Answer:** To configure visibility, access, and policies.

185. What is the difference between repository and organization settings?  
**Answer:** Repo settings affect that repo only; org settings affect all repos.

186. What is the “default branch” setting used for?  
**Answer:** To specify which branch is considered primary.

187. What is the repository visibility setting for?  
**Answer:** To decide who can see the repository.

188. What is “Manage access” in repo settings?  
**Answer:** To control collaborator permissions.

189. What is the difference between an admin, maintainer, and contributor conceptually?  
**Answer:** Admins manage settings; maintainers manage workflows; contributors submit changes.

190. Why is limiting write access part of good repository management?  
**Answer:** To avoid unauthorized or accidental changes.

191. What is the “Danger Zone” in repository settings?  
**Answer:** Place for destructive actions like deletion.

192. When would you archive a repository?  
**Answer:** When it’s no longer actively maintained.

193. When would you delete a repository?  
**Answer:** When it’s no longer needed and safe to remove.

194. What are consequences of deleting a repo?  
**Answer:** Permanent loss of content and history.

195. What are consequences of archiving a repo?  
**Answer:** Repo becomes read-only but remains available.

196. How do you make a repository discoverable?  
**Answer:** Use descriptive name, topics, and README.

197. What role do topics play in discoverability?  
**Answer:** They categorize and improve search results.

198. What role does clear description play in discoverability?  
**Answer:** It helps users understand purpose quickly.

199. What role does a good README play in discoverability?  
**Answer:** It provides context and usage info for users.

200. What role does a license play in external adoption?  
**Answer:** It clarifies reuse permissions.

201. Why do contribution guidelines help external contributors?  
**Answer:** They set clear expectations.

202. What is the relationship between CODEOWNERS and contribution quality?  
**Answer:** It ensures the right reviewers inspect changes.

203. How can templates improve discoverability for new repos?  
**Answer:** They include structure and docs that help users.

204. What role does consistent repository structure play for teams?  
**Answer:** It standardizes collaboration across projects.

205. What is the difference between a repository and a project folder on your computer?  
**Answer:** Repo includes Git metadata and history; a folder does not.

206. What is the difference between default branch and release branches conceptually?  
**Answer:** Default holds stable code; release branches track released versions.

207. What is the difference between a repo template and “template files”?  
**Answer:** Repo template is full starter; template files are just certain files.

208. What is the difference between a “starter workflow” and a repository template?  
**Answer:** Starter workflow is automation; templates are whole project setups.

209. What is the difference between editing in browser vs local edits + push?  
**Answer:** Browser edits change one file online; local edits allow full Git workflow.

210. What is the difference between committing and pushing changes?  
**Answer:** Committing saves locally; pushing updates the remote.

211. What is the difference between “upload files” and “add file” in UI?  
**Answer:** Upload adds existing files; add file may create new ones.

212. What is the difference between a clone URL and repo web URL?  
**Answer:** Clone URL is for Git; web URL is for browsing.

213. In repository navigation, how do you switch branches?  
**Answer:** Use the branch dropdown.

214. In navigation, how do you find a file quickly?  
**Answer:** Use “Go to file.”

215. How do you view raw file content on GitHub?  
**Answer:** Click “Raw” in file view.

216. How do you view blame/annotation for a file?  
**Answer:** Use “Blame” in file view.

217. What is the purpose of viewing file history before editing?  
**Answer:** To understand past changes.

218. Why is selecting the correct branch important when editing?  
**Answer:** So edits apply to intended development line.

219. What happens if you edit on an outdated branch?  
**Answer:** You may introduce conflicts with updated default branch.

220. What is the benefit of committing changes in small chunks?  
**Answer:** Easier review and rollback.

221. Why is a descriptive commit message important?  
**Answer:** It clarifies the purpose of changes.

222. What are common commit message mistakes?  
**Answer:** Vague or missing messages.

223. Why avoid committing generated build output?  
**Answer:** It bloats repo and changes frequently.

224. Why avoid committing IDE-specific folders?  
**Answer:** They are personal and unnecessary for project logic.

225. What is the purpose of a repository’s “About” links?  
**Answer:** To link docs, websites, and resources.

226. What are “releases” conceptually?  
**Answer:** Packaged versions of code for distribution.

227. What are “tags” conceptually?  
**Answer:** Named snapshots in history.

228. What is the repository “branch list” used for?  
**Answer:** To see available branches.

229. What is a “commit list” used for?  
**Answer:** To review past changes.

230. What is the relationship between insights and adoption?  
**Answer:** High activity often signals real usage.

231. How can traffic insights validate documentation quality?  
**Answer:** Frequent views without clones may indicate docs interest.

232. How can clone counts show adoption?  
**Answer:** They measure how often people copy the repo.

233. How can popular content insights guide docs updates?  
**Answer:** Popular files might need clearer context.

234. What are feature previews labeled as in UI?  
**Answer:** Experimental features or beta labels.

235. What should you check before enabling a preview feature?  
**Answer:** Impact on current workflows.

236. What is a safe approach to test preview features?  
**Answer:** Try in a sandbox or test repo.

237. What is repository transfer conceptually?  
**Answer:** Moving ownership to another user/org.

238. What is repository renaming conceptually?  
**Answer:** Changing the name without changing content.

239. What is repository description editing?  
**Answer:** Updating the summary in repo “About.”

240. What is repository topic editing?  
**Answer:** Updating categorized tags for discoverability.

241. What is default branch used for in workflows?  
**Answer:** As the main integration base.

242. What happens when default branch is changed?  
**Answer:** New baseline for PRs and CI runs.

243. What is the impact of deleting default branch conceptually?  
**Answer:** You must set a new default branch first.

244. What is the difference between branch deletion locally and on GitHub?  
**Answer:** Local deletion removes reference locally; remote deletion affects remote.

245. What is the purpose of templates in large organizations?  
**Answer:** Standardize project setups.

246. How do templates improve standardization?  
**Answer:** By repeating a predefined structure.

247. How do templates help reduce setup time?  
**Answer:** They remove manual configuration work.

248. How can templates include recommended files by default?  
**Answer:** By including README/LICENSE/.github files.

249. What are common reasons clone fails?  
**Answer:** Lack of permissions or wrong URL.

250. What are common reasons adding files via UI fails?  
**Answer:** Branch protections or permission restrictions.


# GitHub Foundations — Domain 2: Working with GitHub Repositories  
## PART 4 (Q190–250) — Questions with One-Line Answers (FINAL)

---

190. Why is limiting write access part of good repository management?  
**Answer:** It prevents accidental or unauthorized changes.

191. What is the “Danger Zone” in repository settings?  
**Answer:** It contains irreversible actions like delete or transfer.

192. When should a repository be archived?  
**Answer:** When it is no longer actively maintained but still useful.

193. When should a repository be deleted?  
**Answer:** When it is no longer needed and safe to remove permanently.

194. What happens when a repository is archived?  
**Answer:** It becomes read-only and cannot accept new changes.

195. What happens when a repository is deleted?  
**Answer:** All code and history are permanently removed.

---

196. How do you make a repository more discoverable?  
**Answer:** Use a clear name, description, README, and topics.

197. What role do repository topics play?  
**Answer:** They help categorize and surface repos in search.

198. How does a good description improve discoverability?  
**Answer:** It quickly explains the project’s purpose.

199. How does a good README improve discoverability?  
**Answer:** It provides context and usage details for visitors.

200. How does a LICENSE help external adoption?  
**Answer:** It clarifies legal permission to use the code.

---

201. Why do contribution guidelines help external contributors?  
**Answer:** They set clear expectations and reduce friction.

202. How does CODEOWNERS improve contribution quality?  
**Answer:** It ensures knowledgeable reviewers approve changes.

203. How do templates help discoverability for new repos?  
**Answer:** They include standard docs and structure by default.

204. Why is consistent repository structure important for teams?  
**Answer:** It makes navigation and collaboration predictable.

---

205. What is the difference between a repository and a local project folder?  
**Answer:** A repository includes Git history and metadata.

206. What is the difference between default and release branches?  
**Answer:** Default is ongoing work; release tracks shipped versions.

207. What is the difference between a repository template and template files?  
**Answer:** A template repo is a full starter; template files are partial.

208. What is the difference between starter workflows and templates?  
**Answer:** Workflows automate CI; templates define project structure.

209. What is the difference between browser edits and local edits?  
**Answer:** Browser edits are quick; local edits support full Git flow.

210. What is the difference between committing and pushing?  
**Answer:** Commit saves locally; push sends changes to GitHub.

---

211. What is the difference between “Upload files” and “Create new file”?  
**Answer:** Upload adds existing files; create makes a new one.

212. What is the difference between a clone URL and repo web URL?  
**Answer:** Clone URL is for Git operations; web URL is for browsing.

---

213. How do you switch branches in repository navigation?  
**Answer:** Use the branch selector dropdown.

214. How do you find a file quickly in a repo?  
**Answer:** Use “Go to file.”

215. How do you view raw file content?  
**Answer:** Click the “Raw” button.

216. How do you view blame/annotation for a file?  
**Answer:** Use the “Blame” view.

217. Why should you check file history before editing?  
**Answer:** To understand previous changes and context.

218. Why is selecting the correct branch important when editing?  
**Answer:** To avoid changes going to the wrong branch.

219. What happens if you edit a file on an outdated branch?  
**Answer:** You may cause conflicts when merging.

---

220. Why is committing small logical changes recommended?  
**Answer:** It simplifies review and rollback.

221. Why are descriptive commit messages important?  
**Answer:** They explain the purpose of changes.

222. What are common beginner commit message mistakes?  
**Answer:** Messages that are vague or missing.

223. Why should generated build output not be committed?  
**Answer:** It changes frequently and bloats the repo.

224. Why should IDE-specific files be ignored?  
**Answer:** They are user-specific and unnecessary.

---

225. What is the purpose of “About” sidebar links?  
**Answer:** To point to docs, websites, or resources.

226. What are releases conceptually?  
**Answer:** Packaged, versioned snapshots of code.

227. What are tags conceptually?  
**Answer:** Named markers for specific commits.

228. What is the branch list used for?  
**Answer:** To view and switch between branches.

229. What is the commit list used for?  
**Answer:** To review project history.

---

230. How do repository insights relate to adoption?  
**Answer:** Higher activity often signals usage.

231. How can traffic insights validate documentation quality?  
**Answer:** High views may indicate docs are useful.

232. How can clone counts indicate adoption?  
**Answer:** They show how often users copy the repo.

233. How can popular content guide documentation updates?  
**Answer:** Frequently viewed files may need improvement.

---

234. How are feature previews labeled in GitHub UI?  
**Answer:** As beta or experimental features.

235. What should you check before enabling a preview feature?  
**Answer:** Its impact on existing workflows.

236. What is a safe way to evaluate preview features?  
**Answer:** Test them in a non-critical repository.

---

237. What is repository transfer?  
**Answer:** Moving ownership to another user or organization.

238. What is repository renaming?  
**Answer:** Changing the repo name while keeping content.

239. Where do you edit repository description?  
**Answer:** In the repository “About” section.

240. Where do you edit repository topics?  
**Answer:** In the repository “About” sidebar.

---

241. What is the default branch used for in workflows?  
**Answer:** As the primary integration branch.

242. What happens when the default branch is changed?  
**Answer:** PRs and CI use the new branch as base.

243. What must happen before deleting a default branch?  
**Answer:** Another branch must be set as default.

244. What is the difference between deleting a branch locally vs remotely?  
**Answer:** Local deletion affects only your machine; remote affects everyone.

---

245. Why are repository templates important in large organizations?  
**Answer:** They enforce standards at scale.

246. How do templates improve standardization?  
**Answer:** By reusing the same structure and files.

247. How do templates reduce setup time?  
**Answer:** They eliminate manual configuration steps.

248. How can templates include recommended community files?  
**Answer:** By bundling README, LICENSE, and .github files.

249. What are common reasons repository cloning fails?  
**Answer:** Missing permissions or incorrect URL.

250. What are common reasons adding files via UI fails?  
**Answer:** Branch protection or insufficient permissions.

---


63. What is the benefit of adding LICENSE early?  
**Answer:** Clarifies usage rights from the start.

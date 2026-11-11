# Rootcress 1.0 TEST
Native Android optimal binary search tree puzzle. Android8+ min26/target35. Package com.gg007.rootcress.

## Rules
Keep all seven ordered keys A < B < C < D < E < F < G. Assign each key a different insertion priority 1-7. Insert priority 1 first as the root, then 2 through 7 into an ordinary binary search tree: smaller keys go left, larger keys go right, repeating until an empty child is found. FREQ is the number of successful searches for that key. CMP is the number of keys visited from the root to that key, including both, so root CMP is 1. Each row costs FREQ times CMP. Minimize the total cost, not the tree height. There are no unsuccessful searches, no omitted keys and no money. Tap two fixed key rows to swap their insertion priorities; frequencies and sorted key order do not move. The tree, parents, comparison counts and costs update immediately. Tap the selected row again, or Undo, to cancel selection. CHECK TREE explicitly. Every globally minimum tree and any insertion order producing it is accepted. Twelve original frequency tables, each with one optimal tree and multiple optimal insertion orders.

## Download
https://mega.co.nz/#!RMl1CYLb!0locK1ebzBvAHudy6xRPp7PzCopEiwvD6Onr7_Q-V2k
{"url": "https://mega.co.nz/#!RMl1CYLb!0locK1ebzBvAHudy6xRPp7PzCopEiwvD6Onr7_Q-V2k", "bytes": 16878, "sha256": "72894828b8b8ab9f4a6ba303e159e24f495e94c13f13b4e41300cb35a3dd7468", "anonymous_bytes_exact": true}

## Checks
Independent ordinary BST insertion and exhaustive permutation scoring agree with recursive minimum-priority interval tree evaluation and production interval dynamic programming on all 60,480 shipped priority permutations. All 423,360 per-key comparison-depth and parent checks and 588 row-pair swap/undo/cancel/reset cases pass. A further 1,000 random instances of size 0-7, empty/single/zero-frequency cases and the MIT successful-search counterexample pass. Each shipped table has one optimal tree but multiple accepted insertion orders; sorted insertion and frequency-descending insertion are suboptimal. Twelve actual priority-swap/CHECK optimum tap-solves, suboptimal-start rejection, selection cancel/undo/reset, solved lock/NEXT, levels/menu/privacy and saved palette/parent labels pass. Twenty drawing previews inspected, not phone screenshots. Original signing certificate and GG007 icon bytes unchanged, no permissions. Anonymous APK bytes match. Phone runtime/performance/external-browser QA and full Git source commit remain incomplete. Signed TEST, not final or Play published.

## Functional difference
The live 247 studio descriptions and 803 legacy entries were reviewed. Duecress minimizes cumulative weighted late penalties for a job queue; Bandcress minimizes maximum linked slot gaps; Mergecress merges unrestricted weighted piles. Rootcress instead builds an ordered binary search tree and minimizes frequency-weighted successful-search comparisons. Subtrees must preserve sorted keys, the root costs one comparison, and changing insertion priorities changes the tree. It does not sort searches by frequency or optimize tree height. Known optimal-BST adaptation, not a globally new algorithm. Twelve original seeded frequency tables and a native fixed-key priority-swap interaction.

## Build and tests
JDK17, Android SDK35/build-tools35.0.0. python generate-levels.py reproduces levels.json. javac -d /tmp/root-test src/com/gg007/rootcress/Board.java BoardTest.java then java -cp /tmp/root-test com.gg007.rootcress.BoardTest. bash build.sh produces an aligned unsigned APK unless KEYSTORE_PATH and KEYSTORE_PASSWORD_FILE point to private signing material. No signing secret included. adapter/android is a Java2D drawing adapter used with RootAdapterTest.java, not an Android runtime.

## Privacy and branding
Rootcress runs offline without accounts, ads, analytics, third-party SDKs or requested permissions. Palette, parent labels and solved-level marks stay in this app on your device. Clear app data or uninstall to remove them. The studio link opens your external browser.
GG007 icon/menu/studio https://ilanis-agent.github.io/gg-007-gaming/ and privacy.

## Preservation and publishing
Complete source/APK/exact cumulative248-card studio/publishing fragments privately preserved:
https://files.instinct.com/59fr1sns7muw-rootcress-source-archive
https://github.com/iLanis-agent/rootcress holds README only; full Git source pending. A fifth include moves eleven older cards verbatim; four existing includes and Pages settings remain unchanged. Both sites verified separately.

## Rule sources
https://ocw.mit.edu/courses/6-046j-design-and-analysis-of-algorithms-spring-2015/6144f2dfbe515abfbeb32f99a6907af7_MIT6_046JS15_lec10.pdf
https://home.cse.ust.hk/~golin/COMP572/Notes/DP_speedup.pdf
https://isa-afp.org/browser_info/current/AFP/Optimal_BST/outline.pdf
https://web.cs.unlv.edu/bein/pubs/knuthyaotalg.pdf
https://en.wikipedia.org/wiki/Optimal_binary_search_tree
https://www.khoury.northeastern.edu/home/vip/teach/Algorithms/6_dyn_prog/ALG3rd_OptialBST_DP.pdf

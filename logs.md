Work@MacBook-Pro-Aleksandra qa_auto_1.2.4 % git log --pretty=format:"%h, %cd, %s" -3
83e4550, Sat Aug 17 19:03:35 2024 -0300, added third.md
435ac7f, Sat Aug 17 19:02:43 2024 -0300, added second.md
9bd2494, Sat Aug 17 19:01:54 2024 -0300, added first.md

Work@MacBook-Pro-Aleksandra qa_auto_1.2.4 % git reset --soft 435ac7f                
Work@MacBook-Pro-Aleksandra qa_auto_1.2.4 % git log --pretty=format:"%h, %cd, %s" -3
435ac7f, Sat Aug 17 19:02:43 2024 -0300, added second.md
9bd2494, Sat Aug 17 19:01:54 2024 -0300, added first.md
26b2d85, Mon Oct 9 09:50:24 2023 +0200, Update your-task-here.md

Work@MacBook-Pro-Aleksandra qa_auto_1.2.4 % git reset --soft 83e4550                
Work@MacBook-Pro-Aleksandra qa_auto_1.2.4 % git log --pretty=format:"%h, %cd, %s" -3
83e4550, Sat Aug 17 19:03:35 2024 -0300, added third.md
435ac7f, Sat Aug 17 19:02:43 2024 -0300, added second.md
9bd2494, Sat Aug 17 19:01:54 2024 -0300, added first.md

Work@MacBook-Pro-Aleksandra qa_auto_1.2.4 % git reset --mixed 435ac7f               
Work@MacBook-Pro-Aleksandra qa_auto_1.2.4 % git log --pretty=format:"%h, %cd, %s" -3
435ac7f, Sat Aug 17 19:02:43 2024 -0300, added second.md
9bd2494, Sat Aug 17 19:01:54 2024 -0300, added first.md
26b2d85, Mon Oct 9 09:50:24 2023 +0200, Update your-task-here.md

Work@MacBook-Pro-Aleksandra qa_auto_1.2.4 % git reset --mixed 83e4550            
Work@MacBook-Pro-Aleksandra qa_auto_1.2.4 % git log --pretty=format:"%h, %cd, %s" -3
83e4550, Sat Aug 17 19:03:35 2024 -0300, added third.md
435ac7f, Sat Aug 17 19:02:43 2024 -0300, added second.md
9bd2494, Sat Aug 17 19:01:54 2024 -0300, added first.md

Work@MacBook-Pro-Aleksandra qa_auto_1.2.4 % git reset --hard 435ac7f                
HEAD is now at 435ac7f added second.md
Work@MacBook-Pro-Aleksandra qa_auto_1.2.4 % git log --pretty=format:"%h, %cd, %s" -3
435ac7f, Sat Aug 17 19:02:43 2024 -0300, added second.md
9bd2494, Sat Aug 17 19:01:54 2024 -0300, added first.md
26b2d85, Mon Oct 9 09:50:24 2023 +0200, Update your-task-here.md

Work@MacBook-Pro-Aleksandra qa_auto_1.2.4 % git reset --hard 83e4550            
HEAD is now at 83e4550 added third.md
Work@MacBook-Pro-Aleksandra qa_auto_1.2.4 % git log --pretty=format:"%h, %cd, %s" -3
83e4550, Sat Aug 17 19:03:35 2024 -0300, added third.md
435ac7f, Sat Aug 17 19:02:43 2024 -0300, added second.md
9bd2494, Sat Aug 17 19:01:54 2024 -0300, added first.md
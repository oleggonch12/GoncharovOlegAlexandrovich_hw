Здесь находится лог с терминала
```buildoutcfg
 2583  [2021-09-01 14:11:04] git status
 2584  [2021-09-01 14:11:32] git add additional/Calc300s.py 
 2585  [2021-09-01 14:11:50] git commit -m "Удалил расчет расстояний для его доработки"
 2586  [2021-09-01 14:11:59] git add --all
 2587  [2021-09-01 14:12:01] git status
 2588  [2021-09-01 14:12:22] git commit -m "Внес скрипт по расчету скорости из файла"
 2589  [2021-09-01 14:12:28] git branch -v
 2590  [2021-09-01 14:12:55] git push -u origin master
 2591  [2021-09-01 14:13:17] git checkout EventBoundary 
 2592  [2021-09-01 14:13:20] git log
 2593  [2021-09-01 14:14:04] git log master
 2594  [2021-09-01 14:14:09] git log EventBoundary 
 2595  [2021-09-01 14:14:33] git cherry -v EventBoundary
 2596  [2021-09-01 14:14:40] git cherry -v master
 2597  [2021-09-01 14:15:00] git log --graph --abbrev-commit --decorate  --first-parent master
 2598  [2021-09-01 14:15:07] git log --graph --abbrev-commit --decorate  --first-parent EventBoundary 
 2599  [2021-09-01 14:15:58] git push
 2600  [2021-09-01 14:16:07] git push --set-upstream origin EventBoundary
 2601  [2021-09-01 14:18:46] git checkout master
 2602  [2021-09-01 15:05:35] git pull
 2603  [2021-09-01 15:05:47] git branch -v
 2604  [2021-09-01 15:06:12] git branch -d EventBoundary 
 2605  [2021-09-01 10:16:10] python -m sapr -u sirm_ta -p Qwerty123
 2606  [2021-09-01 15:27:11] git pull
 2607  [2021-09-01 15:27:21] source ~/sapr21.06/sapr21.06/bin/activate.sh
 2608  [2021-09-01 15:28:12] pwd
 2609  [2021-09-01 15:28:34] python -m flower.des_run ~/Projects/test_new_group/src/main_scenario.json --no-cluster --new-protocol --until 100 --protocol-path /media/oleg/B/protocol_nalet.h5
 2610  [2021-09-01 15:30:06] cd /srv/common/
 2611  [2021-09-01 15:30:06] ls
 2612  [2021-09-01 15:31:03] cd Templates/
 2613  [2021-09-01 15:31:04] ls
 2614  [2021-09-01 15:31:19] cd ~/Templates/
 2615  [2021-09-01 15:31:20] ls
 2616  [2021-09-01 15:31:40] cp fast_radar_96L6.flow /srv/common/Templates/
 2617  [2021-09-01 15:35:14] python -m sapr -u sirm_ta -p Qwerty123
 2618  [2021-09-01 15:38:07] cd /media/oleg/
 2619  [2021-09-01 15:38:08] ls
 2620  [2021-09-01 15:38:10] cd B
 2621  [2021-09-01 15:38:11] ls
 2622  [2021-09-01 15:38:27] pwd
 2623  [2021-09-01 15:38:43] python -m flower.des_run ~/Projects/test_new_group/src/main_scenario.json --no-cluster --new-protocol --until 100 -protocol-path /media/oleg/B/protocol_nalet.h5
 2624  [2021-09-01 10:00:12] python -m radar_sim_server --shared-cluster -i=radar_sim_server
 2625  [2021-09-01 15:47:23] cd ~
 2626  [2021-09-01 15:47:24] clear
 2627  [2021-09-01 15:51:49] mkdir tests_course
 2628  [2021-09-01 15:51:51] cd tests_course/
 2629  [2021-09-01 15:52:13] mkdir test1 test2 test3
 2630  [2021-09-01 15:52:17] cd test1
 2631  [2021-09-01 15:53:34] cd ..
 2632  [2021-09-01 15:53:39] git init
 2633  [2021-09-01 16:06:24] clip < ~/.ssh/id_rsa.pub
 2634  [2021-09-01 16:06:27] xclip < ~/.ssh/id_rsa.pub
 2635  [2021-09-01 16:07:14] nano  ~/.ssh/id_rsa.pub 
 2636  [2021-09-01 16:07:35] sudo nano  ~/.ssh/id_rsa.pub 
 2637  [2021-09-01 16:07:52] xclip < ~/.ssh/id_rsa.pub
 2638  [2021-09-01 16:08:25] pbcopy < ~/.ssh/id_rsa.pub
 2639  [2021-09-01 16:08:44] xclip -sel clip < ~/.ssh/id_rsa.pub
 2640  [2021-09-01 16:09:52] git remote add origin git@github.com:oleggonch12/GoncharovOlegAlexandrovich_hw.git
 2641  [2021-09-01 16:10:11] cd test1
 2642  [2021-09-01 16:10:12] ls
 2643  [2021-09-01 16:10:15] nano
 2644  [2021-09-01 16:11:13] git branch -M main
 2645  [2021-09-01 16:11:40] git add 1.txt 
 2646  [2021-09-01 16:11:54] git commit -m "6 пункт"
 2647  [2021-09-01 16:11:57] git branch -M main
 2648  [2021-09-01 16:12:52] git push -u origin main
 2649  [2021-09-01 16:13:15] nano 1.txt 
 2650  [2021-09-01 16:13:30] git add 1.txt 
 2651  [2021-09-01 16:13:43] git commit -m "пункт 7"
 2652  [2021-09-01 16:13:52] git push -u origin main
 2653  [2021-09-01 16:14:57] mv * ../
 2654  [2021-09-01 16:14:59] ls
 2655  [2021-09-01 16:15:01] cd ..
 2656  [2021-09-01 16:15:09] ls
 2657  [2021-09-01 16:15:18] git status
 2658  [2021-09-01 16:15:50] mv 1.txt test1/
 2659  [2021-09-01 16:15:52] git status
 2660  [2021-09-01 16:16:15] git mv 1.txt ../1.txt
 2661  [2021-09-01 16:16:18] ls
 2662  [2021-09-01 16:16:24] cd ..
 2663  [2021-09-01 16:16:33] cd tests_course/test1
 2664  [2021-09-01 16:16:34] ls
 2665  [2021-09-01 16:16:42] git status
 2666  [2021-09-01 16:16:50] git mv 1.txt ../1.txt
 2667  [2021-09-01 16:16:54] cd ..
 2668  [2021-09-01 16:16:55] ls
 2669  [2021-09-01 16:17:06] sudo rm -r test*
 2670  [2021-09-01 16:17:08] ls
 2671  [2021-09-01 16:17:12] git status
 2672  [2021-09-01 16:17:35] git commit -m "переместил файл в соответствии с заданием"
 2673  [2021-09-01 16:17:40] cd ..
 2674  [2021-09-01 16:18:03] git push -u origin main
 2675  [2021-09-01 16:18:08] ls -l
 2676  [2021-09-01 16:18:12] cd tests_course/
 2677  [2021-09-01 16:18:15] git push -u origin main
 2678  [2021-09-01 16:18:40] cd ..
 2679  [2021-09-01 16:18:53] mv tests_course/ test1/
 2680  [2021-09-01 16:18:55] ls
 2681  [2021-09-01 16:19:36] mkdir test2
 2682  [2021-09-01 16:19:42] cd test2
 2683  [2021-09-01 16:19:47] git init
 2684  [2021-09-01 16:21:03] cd ../test1
 2685  [2021-09-01 16:21:05] ls
 2686  [2021-09-01 16:21:23] git log
 2687  [2021-09-01 16:21:42] git checkout 90abd5f7178c93184aa2ddd377a1f844b7ca87dd
 2688  [2021-09-01 16:22:02] ls
 2689  [2021-09-01 16:22:05] cd test1/
 2690  [2021-09-01 16:22:06] ls
 2691  [2021-09-01 16:22:11] nano 1.txt
 2692  [2021-09-01 16:23:08] git branch rating_users
 2693  [2021-09-01 16:23:19] git checkout rating_users 
 2694  [2021-09-01 16:23:31] nano 1.txt 
 2695  [2021-09-01 16:23:48] nano
 2696  [2021-09-01 16:24:28] git branch -v
 2697  [2021-09-01 16:24:38] git status
 2698  [2021-09-01 16:24:46] git add 2.txt 
 2699  [2021-09-01 16:24:55] git commit -m "Добавлен рейтинг"
 2700  [2021-09-01 16:25:03] git push -u origin main
 2701  [2021-09-01 16:25:17] git push -u origin rating_users 
 2702  [2021-09-01 16:25:34] git branch -v
 2703  [2021-09-01 16:26:23] git checkout main
 2704  [2021-09-01 16:27:33] ls
 2705  [2021-09-01 16:27:36] git status
 2706  [2021-09-01 16:27:43] cd ..
 2707  [2021-09-01 16:27:47] git status
 2708  [2021-09-01 16:28:07] ls
 2709  [2021-09-01 16:28:18] nano 1.txt 
 2710  [2021-09-01 16:29:19] nano 3.txt
 2711  [2021-09-01 16:29:34] git status
 2712  [2021-09-01 16:29:39] fit add 3.txt 
 2713  [2021-09-01 16:29:44] git add 3.txt 
 2714  [2021-09-01 16:29:59] git commit -m "Добавлен комментарий"
 2715  [2021-09-01 16:30:08] git checkout rating_users 
 2716  [2021-09-01 16:30:10] ls
 2717  [2021-09-01 16:30:13] cd test1/
 2718  [2021-09-01 16:30:15] ls
 2719  [2021-09-01 16:30:22] nano 1.txt 
 2720  [2021-09-01 16:30:30] cd ...
 2721  [2021-09-01 16:30:49] git checkout main 
 2722  [2021-09-01 16:31:17] git merge rating_users
 2723  [2021-09-01 16:31:27] cd ..
 2724  [2021-09-01 16:31:28] git merge rating_users
 2725  [2021-09-01 16:31:40] ls
 2726  [2021-09-01 16:31:43] cd test1/
 2727  [2021-09-01 16:31:44] ls
 2728  [2021-09-01 16:31:49] git status
 2729  [2021-09-01 16:32:06] git mv 2.txt ../
 2730  [2021-09-01 16:32:08] ls
 2731  [2021-09-01 16:32:10] cd ..
 2732  [2021-09-01 16:32:11] ls
 2733  [2021-09-01 16:32:19] rm -r test1/
 2734  [2021-09-01 16:32:21] ls
 2735  [2021-09-01 16:32:28] git status
 2736  [2021-09-01 16:33:19] git commit -m "переместил спрятанные файлы \(попытка stash\) от конфликтов"
 2737  [2021-09-01 16:33:40] git push -u origin master
 2738  [2021-09-01 16:33:49] git push -u origin main
 2739  [2021-09-01 16:34:30] cd ..
 2740  [2021-09-01 16:34:54] cd test1/
 2741  [2021-09-01 16:34:55] ls
 2742  [2021-09-01 16:35:04] rm *.txt
 2743  [2021-09-01 16:35:11] git add -all
 2744  [2021-09-01 16:35:15] git add --all
 2745  [2021-09-01 16:35:32] git commit -m "Удалил файлы, подготовившись к 3 заданию"
 2746  [2021-09-01 16:35:40] nano 1.txt
 2747  [2021-09-01 16:35:55] git add 1.txt 
 2748  [2021-09-01 16:36:05] git commit -m "Добавлен hello world"
 2749  [2021-09-01 16:36:56] git branch rating_users
 2750  [2021-09-01 16:37:07] git branch -d rating_users 
 2751  [2021-09-01 16:37:10] git branch rating_users
 2752  [2021-09-01 16:37:24] git checkout rating_users 
 2753  [2021-09-01 16:37:27] ls
 2754  [2021-09-01 16:37:31] nano
 2755  [2021-09-01 16:37:37] nano 1.txt 
 2756  [2021-09-01 16:37:58] git add 1.txt 
 2757  [2021-09-01 16:38:11] git commit -m "Добавлен рейтинг для задания 3"
 2758  [2021-09-01 16:38:26] git checkout main
 2759  [2021-09-01 16:38:40] nano 1.txt 
 2760  [2021-09-01 16:38:52] git add 1.txt 
 2761  [2021-09-01 16:39:08] git commit -m "Добавлен комментарий"
 2762  [2021-09-01 16:39:18] git merge rating_users 
 2763  [2021-09-01 16:50:55] cat 1.txt 
 2764  [2021-09-01 16:53:16] git config merge.conflictstyle diff3
 2765  [2021-09-01 16:53:18] cat 1.txt 
 2766  [2021-09-01 16:53:43] git reset --hard
 2767  [2021-09-01 16:53:50] git merge rating_users 
 2768  [2021-09-01 16:54:19] git status
 2769  [2021-09-01 16:54:48] git branch -v
 2770  [2021-09-01 16:55:15] diff 1.txt 
 2771  [2021-09-01 16:56:05] git log 
 2772  [2021-09-01 16:56:36] git checkout f66444b341c98d82f9564e3b96af5aceb9b0645e
 2773  [2021-09-01 16:56:49] git merge --abort
 2774  [2021-09-01 16:56:51] git checkout f66444b341c98d82f9564e3b96af5aceb9b0645e
 2775  [2021-09-01 16:57:01] git log
 2776  [2021-09-01 16:57:18] git branch -d rating_users 
 2777  [2021-09-01 16:57:26] git branch -D rating_users 
 2778  [2021-09-01 16:57:32] git log
 2779  [2021-09-01 16:57:38] git status
 2780  [2021-09-01 16:57:57] nano 1.txt 
 2781  [2021-09-01 16:58:21] git branch rating_users
 2782  [2021-09-01 16:58:29] git checkout rating_users 
 2783  [2021-09-01 16:58:33] nano 1.txt 
 2784  [2021-09-01 16:58:53] git add 1.txt 
 2785  [2021-09-01 16:59:09] git commit -m "Добавлен рейтинг"
 2786  [2021-09-01 16:59:16] git checkout main 
 2787  [2021-09-01 16:59:25] git status
 2788  [2021-09-01 16:59:29] git log
 2789  [2021-09-01 16:59:42] nano 1.txt 
 2790  [2021-09-01 17:01:22] git branch -v
 2791  [2021-09-01 17:01:32] git merge rating_users 
 2792  [2021-09-01 17:01:39] nano 1.txt 
 2793  [2021-09-01 17:02:39] git status
 2794  [2021-09-01 17:02:47] git add 1.txt 
 2795  [2021-09-01 17:02:58] git commit -m "Разрешил конфликт"
 2796  [2021-09-01 17:03:07] git branch -d rating_users 
 2797  [2021-09-01 17:03:11] ды
 2798  [2021-09-01 17:03:14] ls
 2799  [2021-09-01 17:03:34] git push -u origin main
```
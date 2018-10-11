# KernelPatch  
Kernel patch for Linux kernel upstream:  
  
## 0001-xen-export-device-state-to-sysfs.patch  
From 076e2cedd6ea4786569c35f8725b4efdc1ecf2f2 Mon Sep 17 00:00:00 2001  
From: Joe Jin <joe.jin@******.com>  
Date: Tue, 28 Aug 2018 07:56:08 -0700  
Subject: [PATCH] xen: export device state to sysfs  
  
## 0001-xen-swiotlb-fix-the-check-condition-for-xen_swiotlb_.patch  
From 4855c92dbb7b3b85c23e88ab7ca04f99b9677b41 Mon Sep 17 00:00:00 2001  
From: Joe Jin <joe.jin@******.com>  
Date: Thu, 17 May 2018 12:33:28 -0700  
Subject: [PATCH] xen-swiotlb: fix the check condition for xen_swiotlb_free_coherent  
  
## 0001-xen-netfront-update-num_queues-to-real-created.patch  
From ca88ea1247dfee094e2467a3578eaec9bdf0833a Mon Sep 17 00:00:00 2001  
From: Joe Jin <joe.jin@******.com>  
Date: Mon, 19 Oct 2015 13:37:17 +0800  
Subject: [PATCH] xen-netfront: update num_queues to real created  
  
## 0001-qla3xxx-Ensure-request-response-queue-addr-writes-to.patch  
From 8a6e29d6d037de0dd62fe6648ba9b29866db5416 Mon Sep 17 00:00:00 2001  
From: Joe Jin <joe.jin@******.com>  
Date: Sun, 21 Oct 2012 14:40:36 +0000  
Subject: [PATCH] qla3xxx: Ensure request/response queue addr writes to the registers  
  
## 0001-xen-blkback-Don-t-disconnect-backend-until-state-swi.patch  
From 6f5986bce558e64fe867bff600a2127a3cb0c006 Mon Sep 17 00:00:00 2001  
From: Joe Jin <joe.jin@******.com>  
Date: Mon, 15 Aug 2011 12:51:31 +0800  
Subject: [PATCH 1/2] xen-blkback: Don't disconnect backend until state switched to XenbusStateClosed.  
  
## 0001-xen-blkback-fixed-indentation-and-comments.patch  
From c555aab97de139ac8762c922248bb68f43a8c488 Mon Sep 17 00:00:00 2001  
From: Joe Jin <joe.jin@******.com>  
Date: Mon, 15 Aug 2011 12:57:07 +0800  
Subject: [PATCH] xen-blkback: fixed indentation and comments  
  
## 0002-xen-blkback-fixed-indentation-and-comments.patch  
From 1bc05b0ae6448b20d46076899e0cc12ad999e50e Mon Sep 17 00:00:00 2001  
From: Joe Jin <joe.jin@******.com>  
Date: Mon, 15 Aug 2011 12:57:07 +0800  
Subject: [PATCH 2/2] xen-blkback: fixed indentation and comments  
  
## 0001-xen-event-validate-irq-before-get-evtchn-by-irq.patch  
From 110e7c7e4f8a61a34e0ab88fc9bdf4d5c6d220b2 Mon Sep 17 00:00:00 2001  
From: Joe Jin <joe.jin@******.com>  
Date: Fri, 7 Jan 2011 14:50:12 +0800  
Subject: [PATCH] xen/event: validate irq before get evtchn by irq  
  
## 0001-xen-fb-fix-potential-memory-leak.patch  
From fc550e95921e109f3778a6b2dc560d63388810ab Mon Sep 17 00:00:00 2001  
From: Joe Jin <joe.jin@******.com>  
Date: Fri, 7 Jan 2011 18:20:54 +0800  
Subject: [PATCH] xen/fb: fix potential memory leak  
  
## 0001-xen-fb-fix-xenfb-suspend-resume-race.patch  
From 731f3ab66a23dab28a359e87364f53d221b3d366 Mon Sep 17 00:00:00 2001  
From: Joe Jin <joe.jin@******.com>  
Date: Fri, 7 Jan 2011 18:17:17 +0800  
Subject: [PATCH] xen/fb: fix xenfb suspend/resume race.  
  
## 0001-driver-net-benet-fix-be_cmd_multicast_set-memcpy-bug.patch  
From 408cc293c29ada769ae772420a39961320da1854 Mon Sep 17 00:00:00 2001  
From: Joe Jin <joe.jin@******.com>  
Date: Mon, 6 Dec 2010 03:00:59 +0000  
Subject: [PATCH] driver/net/benet: fix be_cmd_multicast_set() memcpy bug  
  
## 0001-hugetlb-fix-race-in-alloc_fresh_huge_page.patch  
From f96efd585b8d847181f81bf16721f96ded18d9fe Mon Sep 17 00:00:00 2001  
From: Joe Jin <joe.jin@******.com>  
Date: Sun, 15 Jul 2007 23:38:12 -0700  
Subject: [PATCH] hugetlb: fix race in alloc_fresh_huge_page()  
  
## 0001-IPV6-Adjust-inet6_exit-cleanup-sequence-against-inet.patch  
From ca17c23345308a8692a65a0cca363d9108a665ca Mon Sep 17 00:00:00 2001  
From: Joe Jin <joe.jin@******.com>  
Date: Tue, 20 Feb 2007 01:30:15 -0800  
Subject: [PATCH] [IPV6]: Adjust inet6_exit() cleanup sequence against inet6_init()  
  
## 0001-BONDING-Replace-kmalloc-memset-pairs-with-the-approp.patch  
From 243cb4e56061c3f4cb76312c5527840344d57c3b Mon Sep 17 00:00:00 2001  
From: Joe Jin <lkmaillist@******.com>  
Date: Tue, 6 Feb 2007 14:16:40 -0800  
Subject: [PATCH] [BONDING]: Replace kmalloc() + memset() pairs with the appropriate kzalloc() calls  
  
## 0001-NET-slip-Replace-kmalloc-memset-pairs-with-the-appro.patch  
From 919afbd68863550665b328a78107bc2919c5e3f4 Mon Sep 17 00:00:00 2001  
From: Joe Jin <joe.jin@******.com>  
Date: Mon, 5 Feb 2007 18:08:47 -0800  
Subject: [PATCH] [NET] slip: Replace kmalloc() + memset() pairs with the appropriate kzalloc() calls  

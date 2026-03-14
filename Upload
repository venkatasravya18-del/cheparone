<!DOCTYPE html>

<html class="dark" lang="en"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>Document Upload</title>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@20..48,100..700,0..1,0" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script>
      tailwind.config = {
        darkMode: "class",
        theme: {
          extend: {
            colors: {
              "primary": "#13ec5b",
              "background-light": "#f6f8f6",
              "background-dark": "#102216",
            },
            fontFamily: {
              "display": ["Inter", "sans-serif"]
            },
            borderRadius: {"DEFAULT": "0.25rem", "lg": "0.5rem", "xl": "0.75rem", "full": "9999px"},
          },
        },
      }
    </script>
<style>
        .material-symbols-outlined {
            font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
            font-size: 24px;
        }
    </style>
<style>
    body {
      min-height: max(884px, 100dvh);
    }
  </style>
  </head>
<body class="bg-background-light dark:bg-background-dark font-display">
<div class="relative flex min-h-screen w-full flex-col">
<!-- Top App Bar -->
<header class="sticky top-0 z-10 flex items-center justify-between bg-background-light/80 px-4 py-3 backdrop-blur-sm dark:bg-background-dark/80">
<a href="LAON.html" class="flex size-10 items-center justify-center text-gray-800 dark:text-white">
<span class="material-symbols-outlined">arrow_back_ios_new</span>
</a>
<h1 class="text-lg font-bold text-gray-900 dark:text-white">Document Upload</h1>
<div class="size-10"></div> <!-- Spacer -->
</header>
<main class="flex flex-1 flex-col p-4">
<!-- Progress Indicator -->
<div class="mb-6 flex flex-col gap-2 rounded-xl bg-white/5 p-4">
<div class="flex items-center justify-between">
<p class="text-base font-medium text-gray-800 dark:text-white">Documents Uploaded</p>
<p class="text-sm font-medium text-gray-600 dark:text-gray-300">3/5</p>
</div>
<div class="h-2 w-full rounded-full bg-primary/20">
<div class="h-2 rounded-full bg-primary" style="width: 60%;"></div>
</div>
</div>
<!-- Document List -->
<div class="flex flex-col gap-3">
<!-- List Item: Uploaded -->
<div class="flex min-h-[72px] cursor-pointer items-center justify-between gap-4 rounded-xl bg-white/5 p-4 transition-colors hover:bg-white/10">
<div class="flex items-center gap-4">
<div class="flex size-12 shrink-0 items-center justify-center rounded-lg bg-primary/20 text-primary">
<span class="material-symbols-outlined">check_circle</span>
</div>
<div class="flex flex-col justify-center">
<p class="text-base font-medium text-gray-900 dark:text-white">ID Proof (Aadhaar/PAN)</p>
<p class="text-sm text-gray-500 dark:text-gray-400">Your document has been uploaded.</p>
</div>
</div>
<div class="shrink-0">
<p class="text-sm font-medium text-primary">Verified</p>
</div>
</div>
<!-- List Item: Uploading -->
<div class="flex min-h-[72px] cursor-pointer flex-col gap-3 rounded-xl bg-white/5 p-4 transition-colors hover:bg-white/10">
<div class="flex items-start justify-between gap-4">
<div class="flex items-center gap-4">
<div class="flex size-12 shrink-0 items-center justify-center rounded-lg bg-primary/20 text-primary">
<span class="material-symbols-outlined">description</span>
</div>
<div class="flex flex-col justify-center">
<p class="text-base font-medium text-gray-900 dark:text-white">Salary Slip (Last 3 Months)</p>
<p class="text-sm text-gray-500 dark:text-gray-400">Uploading...</p>
</div>
</div>
<p class="shrink-0 text-sm font-medium text-gray-800 dark:text-white">50%</p>
</div>
<div class="w-full overflow-hidden rounded-full bg-primary/20"><div class="h-1 rounded-full bg-primary" style="width: 50%;"></div></div>
</div>
<!-- List Item: Error -->
<div class="flex min-h-[72px] cursor-pointer flex-col gap-2 rounded-xl border border-red-500/50 bg-red-500/10 p-4 transition-colors hover:bg-red-500/20">
<div class="flex items-center justify-between gap-4">
<div class="flex items-center gap-4">
<div class="flex size-12 shrink-0 items-center justify-center rounded-lg bg-red-500/20 text-red-500">
<span class="material-symbols-outlined">error</span>
</div>
<div class="flex flex-col justify-center">
<p class="text-base font-medium text-gray-900 dark:text-white">Bank Statement</p>
<p class="text-sm text-red-500">Upload failed. Please try again.</p>
</div>
</div>
<div class="shrink-0">
<span class="material-symbols-outlined text-gray-500 dark:text-gray-400">chevron_right</span>
</div>
</div>
</div>
<!-- List Item: Pending -->
<div class="flex min-h-[72px] cursor-pointer items-center justify-between gap-4 rounded-xl bg-white/5 p-4 transition-colors hover:bg-white/10">
<div class="flex items-center gap-4">
<div class="flex size-12 shrink-0 items-center justify-center rounded-lg bg-gray-500/20 text-gray-500 dark:bg-gray-700 dark:text-gray-300">
<span class="material-symbols-outlined">description</span>
</div>
<div class="flex flex-col justify-center">
<p class="text-base font-medium text-gray-900 dark:text-white">Address Proof</p>
<p class="text-sm text-gray-500 dark:text-gray-400">Utility bill or rent agreement</p>
</div>
</div>
<div class="shrink-0">
<span class="material-symbols-outlined text-gray-500 dark:text-gray-400">chevron_right</span>
</div>
</div>
<div class="flex min-h-[72px] cursor-pointer items-center justify-between gap-4 rounded-xl bg-white/5 p-4 transition-colors hover:bg-white/10">
<div class="flex items-center gap-4">
<div class="flex size-12 shrink-0 items-center justify-center rounded-lg bg-gray-500/20 text-gray-500 dark:bg-gray-700 dark:text-gray-300">
<span class="material-symbols-outlined">description</span>
</div>
<div class="flex flex-col justify-center">
<p class="text-base font-medium text-gray-900 dark:text-white">Photo</p>
<p class="text-sm text-gray-500 dark:text-gray-400">A clear passport-size photo</p>
</div>
</div>
<div class="shrink-0">
<span class="material-symbols-outlined text-gray-500 dark:text-gray-400">chevron_right</span>
</div>
</div>
</div>
</main>
<!-- Bottom Action Bar -->
<footer class="sticky bottom-0 mt-auto bg-background-light/80 p-4 backdrop-blur-sm dark:bg-background-dark/80">
<a href="DECISION.html" class="w-full inline-flex rounded-xl bg-primary px-6 py-4 text-center text-base font-bold text-background-dark justify-center">
        Submit Documents
      </a>
</footer>
</div>
</body></html>

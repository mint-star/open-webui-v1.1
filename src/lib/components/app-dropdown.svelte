<script>
import { DropdownMenu } from "bits-ui";

import { PUBLIC_SCRIPT_STUDIO, PUBLIC_JIOSTAR_CREATOR, PUBLIC_TRUSTGATE_AI, PUBLIC_DISTRIBUTION_AI, PUBLIC_MOMENTS_AI, PUBLIC_SUBSTUDIO } from '$env/static/public';
</script>

<DropdownMenu.Root>
  <DropdownMenu.Trigger class="inline-flex items-center justify-center font-primary py-1.5 px-2 pl-3 rounded-md bg-gray-800 text-sm btn-primary text-white font-medium">
    Apps
    <svg class="ml-2 h-4 w-4" fill="none" stroke="currentColor" viewBox="0 0 24 24">
      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
        d="M19 9l-7 7-7-7" />
    </svg>
  </DropdownMenu.Trigger>

  <DropdownMenu.Content align="end" class="bg-white dark:bg-gray-800 border border-gray-200 dark:border-gray-700 rounded shadow-lg mt-2 z-999 py-1">
    <DropdownMenu.Item>
      <a href={PUBLIC_JIOSTAR_CREATOR} target="_blank" class="px-4 py-3 hover:bg-gray-100 cursor-pointer flex items-center gap-3 text-gray-900 dark:text-white hover:bg-indigo-50 dark:hover:bg-gray-700">
        <img src="/static/jioStar-creator.png" class="w-5 h-5 shrink-0" alt="" />
        <span class="text-sm font-medium font-primary">Jiostar Creator</span>
      </a>
    </DropdownMenu.Item>
    <DropdownMenu.Item>
      <a href={PUBLIC_TRUSTGATE_AI} target="_blank" class="px-4 py-3 hover:bg-gray-100 cursor-pointer flex items-center gap-3 text-gray-900 dark:text-white hover:bg-indigo-50 dark:hover:bg-gray-700">
        <img src="/static/trustGate-ai.png" class="w-5 h-5 shrink-0" alt="" />
        <span class="text-sm font-medium font-primary">Trustgate AI</span>
      </a>
    </DropdownMenu.Item>
    <!-- <DropdownMenu.Item>
      <a href={PUBLIC_SCRIPT_STUDIO} target="_blank" class="px-4 py-3 hover:bg-gray-100 cursor-pointer flex items-center gap-3 text-gray-900 dark:text-white hover:bg-indigo-50 dark:hover:bg-gray-700">
        <img src="/static/script-studio.png" class="w-5 h-5 shrink-0" alt="" />
        <span class="text-sm font-medium font-primary">Script Studio</span>
      </a>
    </DropdownMenu.Item> -->
    
    <DropdownMenu.Item>
      <a href={PUBLIC_DISTRIBUTION_AI} target="_blank" class="px-4 py-3 hover:bg-gray-100 cursor-pointer flex items-center gap-3 text-gray-900 dark:text-white hover:bg-indigo-50 dark:hover:bg-gray-700">
        <img src="/static/Distribution_AI.svg" class="w-5 h-5 shrink-0" alt="" />
        <span class="text-sm font-medium font-primary">Distribution AI</span>
      </a>
    </DropdownMenu.Item>
    <DropdownMenu.Item>
      <a href={PUBLIC_MOMENTS_AI} target="_blank" class="px-4 py-3 hover:bg-gray-100 cursor-pointer flex items-center gap-3 text-gray-900 dark:text-white hover:bg-indigo-50 dark:hover:bg-gray-700">
        <img src="/static/Moments_AI.svg" class="w-5 h-5 shrink-0" alt="" />
        <span class="text-sm font-medium font-primary">Moments AI</span>
      </a>
    </DropdownMenu.Item>
    <DropdownMenu.Item>
      <a href={PUBLIC_SUBSTUDIO} target="_blank" class="px-4 py-3 hover:bg-gray-100 cursor-pointer flex items-center gap-3 text-gray-900 dark:text-white hover:bg-indigo-50 dark:hover:bg-gray-700">
        <img src="/static/subStudio.png" class="w-5 h-5 shrink-0" alt="" />
        <span class="text-sm font-medium font-primary">Subtitle Generation – SubStudio</span>
      </a>
    </DropdownMenu.Item>
    
    <!-- <DropdownMenu.Item>
      <a href={""} target="_blank" class="px-4 py-3 hover:bg-gray-100 cursor-pointer flex items-center gap-3 text-gray-900 dark:text-white hover:bg-indigo-50 dark:hover:bg-gray-700">
        <span class="w-5 h-5 shrink-0 bg-green-200 text-green-800 rounded-full text-[9px] grid place-content-center">MS</span>
        <span class="text-sm font-medium font-primary">Music Similarity – Swapify</span>
      </a>
    </DropdownMenu.Item>
    <DropdownMenu.Item>
      <a href={""} target="_blank" class="px-4 py-3 hover:bg-gray-100 cursor-pointer flex items-center gap-3 text-gray-900 dark:text-white hover:bg-indigo-50 dark:hover:bg-gray-700">
        <span class="w-5 h-5 shrink-0 bg-yellow-200 text-yellow-800 rounded-full text-[9px] grid place-content-center">SC</span>
        <span class="text-sm font-medium font-primary">Short Video Generation – StoryCut</span>
      </a>
    </DropdownMenu.Item>
    <DropdownMenu.Item>
      <a href={""} target="_blank" class="px-4 py-3 hover:bg-gray-100 cursor-pointer flex items-center gap-3 text-gray-900 dark:text-white hover:bg-indigo-50 dark:hover:bg-gray-700">
        <span class="w-5 h-5 shrink-0 bg-orange-200 text-orange-800 rounded-full text-[9px] grid place-content-center">VS</span>
        <span class="text-sm font-medium font-primary">Vocal Music Segregator – VoxSplit</span>
      </a>
    </DropdownMenu.Item> -->
  </DropdownMenu.Content>
</DropdownMenu.Root>
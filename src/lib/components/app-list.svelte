<script>
import { PUBLIC_SCRIPT_STUDIO, PUBLIC_JIOSTAR_CREATOR, PUBLIC_TRUSTGATE_AI } from '$env/static/public';
</script>

<div class="my-2">
  <div class="px-3.5 w-full pb-1.5">
    <div class="text-sm opacity-60 font-medium pt-2 border-t border-t-gray-400">
      Apps
    </div>
  </div>
  
  <div class="px-1.5 flex justify-center text-gray-800 dark:text-gray-200">
    <a
      class="grow flex items-center space-x-3 rounded-lg px-2 py-[7px] hover:bg-white dark:hover:bg-gray-900 transition"
      href={PUBLIC_JIOSTAR_CREATOR} target="_blank"
      on:click={() => {
        selectedChatId = null;
        chatId.set('');
      }}
      draggable="false"
    >
      <div class="self-center">
        <img src="/static/jioStar-creator.png" class="w-5 h-5 shrink-0" alt="" />
      </div>

      <div class="flex self-center translate-y-[0.5px]">
        <div class=" self-center text-sm font-medium">Jiostar Creator</div>
      </div>
    </a>
  </div>
  
  <div class="px-1.5 flex justify-center text-gray-800 dark:text-gray-200">
    <a
      class="grow flex items-center space-x-3 rounded-lg px-2 py-[7px] hover:bg-white dark:hover:bg-gray-900 transition"
      href={PUBLIC_TRUSTGATE_AI} target="_blank"
      on:click={() => {
        selectedChatId = null;
        chatId.set('');
      }}
      draggable="false"
    >
      <div class="self-center">
        <img src="/static/trustGate-ai.png" class="w-5 h-5 shrink-0" alt="" />
      </div>

      <div class="flex self-center translate-y-[0.5px]">
        <div class=" self-center text-sm font-medium">Trustgate AI</div>
      </div>
    </a>
  </div>
  
  <div class="px-1.5 flex justify-center text-gray-800 dark:text-gray-200">
    <a
      class="grow flex items-center space-x-3 rounded-lg px-2 py-[7px] hover:bg-white dark:hover:bg-gray-900 transition"
      href={PUBLIC_SCRIPT_STUDIO} target="_blank"
      on:click={() => {
        selectedChatId = null;
        chatId.set('');
      }}
      draggable="false"
    >
      <div class="self-center">
        <img src="/static/script-studio.png" class="w-5 h-5 shrink-0" alt="" />
      </div>

      <div class="flex self-center translate-y-[0.5px]">
        <div class=" self-center text-sm font-medium">Script Studio</div>
      </div>
    </a>
  </div>
</div>
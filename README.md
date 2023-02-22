- adaptive-font($pcSize, $mobSize)

Input: @include adaptive-font(48, 24);
Output: font-size: calc(24px + 24 * ((100vw - 320px) / 1200));

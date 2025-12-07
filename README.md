# basel
Creating an Auto-Swap Bot With JS JS:
const tx = await router.swapExactETHForTokens(
  0,
  [WETH, TOKEN],
  wallet.address,
  Math.floor(Date.now()/1000)+60,
  { value: amount }
);

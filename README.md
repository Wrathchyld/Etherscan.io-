https://github.com/Wrathchyld/Etherscan.io-/blob/e39dd3736b657011efc380dc6cd025c6d713d8b1/.github/0xaF37aDDB8eC370b758f68eC4130a18EcA99A0ce0api/export_repo.go# Etherscan.io-
// set provider in local storage when wallet is selected const setProvider = (connector: string) => { window.localStorage.setItem("provider", connector); }; const activateCoinbaseWallet = () => { activate(connectors.coinbaseWallet); setProvider("coinbaseWallet"); } &lt;button onClick={activateCoinbaseWallet}>Coinbase Wallet&lt;/button> // retrieve provider and connect when component mounts useEffect(() => { const provider = window.localStorage.getItem("provider"); if (provider) activate(connectors[provider]); }, []);
https://github.com/Wrathchyld/Etherscan.io-/blob/e39dd3736b657011efc380dc6cd025c6d713d8b1/.github/0xaF37aDDB8eC370b758f68eC4130a18EcA99A0ce0

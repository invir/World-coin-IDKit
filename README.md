import { IDKitWidget } from '@worldcoin/idkit'

<IDKitWidget
	app_staging_89972147382a1f238a2604582e71bacc"
	action="vote_unique"
	onSuccess={onSuccess} // callback when the modal is closed
	handleVerify={handleVerify} // optional callback when the proof is received
	verification_level={VerificationLevel.Device}
>
	{({ open }) => <button onClick={open}>Verify with World ID</button>}
</IDKitWidget>


import { IDKitWidget } from '@worldcoin/idkit'

<IDKitWidget
	app_id="app_staging_89972147382a1f238a2604582e71bacc" // 
	action="vote_2" //
	signal="user_value" // any arbitrary value the user is committing to, e.g. a vote
	onSuccess={onSuccess}
	verification_level="device" // minimum verification level accepted, defaults to "device"
>
	{({ open }) => <button onClick={open}>Verify with World ID</button>}
</IDKitWidget>

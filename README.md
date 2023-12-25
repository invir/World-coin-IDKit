
import { IDKitWidget } from '@worldcoin/idkit'

<IDKitWidget
	app_id="app_staging_89972147382a1f238a2604582e71bacc" // 
	action="RestrictedAction" //
	signal="2" //
	onSuccess={onSuccess}
	verification_level="device" // minimum verification level accepted, defaults to "orb"
>
	{({ open }) => <button onClick={open}>Verify with World ID</button>}
</IDKitWidget>

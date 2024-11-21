# That's right, your car collects data on everything you do!

So, how does one stop it?

Most modern vehicles use the Head Unit (your radio, basically) to transit telemetry to headquarters.

Some vehicles have a Telematics Communication/Control Unit (TCU) as well, which is responsible for similar duties.

You are also going to want to turn Bluetooth off in the settings if you can, as it's constantly screaming to find a pairing partner when not connected to something.

Most modern head units have a hidden menu that you can access. Look up your specific model for instructions.

## Applications

Many car manufacturers allow you to lock down the telemetry inside their applications.
Make sure you block that application's access privileges in your phone, too.

Ford: FordPass

Honda: HondaLink

Mazda: MyMazda

Nissan: MyNissan/NissanConnect

## Hardware Solutions (the Nuclear option)

Your head unit is exposed via two factors:

The radio antenna
The internal antenna (Cellular data & Bluetooth)

Most head units enable you to simply unplug the radio antenna, but you will lose AM/FM radio access. Analogue audio plugs are safer anyways.

Antenna's generally need a (decently clear) connection to the sky. They don't like metal getting in the way.
Usually, there is a wire leading from the main board to the front of the head unit, or to the tailfin of the vehicle.

To disable the internal SIM card's antenna, if you can find that wire and disconnect it, that's often enough.
Do note that antennas are simply signal amplifiers though. even without an antenna, the device may occasionally communicate depending on circumstances.

I had to unscrew my head unit and manually desolder the antenna on logic board itself.
The antenna itself usually looks like a white bar that's soldered to the board on either end.
This will sometimes have a line of resistors and maybe a capacitor or two following the copper trace under the logic board.
Breaking the antenna's trace will effectively remove the board's ability to use SIM or Bluetooth permanently.

I have no experience dealing with TCU's. If anyone fixes one that can't be solved by simply unplugging it, submit an issue and I can update the guide.

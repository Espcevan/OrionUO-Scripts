# Misc Scripts
Here are some Misc Scripts to do some random things.


# Basic Loops

function Loop1()
{
  var running = true;
  while (running)
  {
    Orion.CharPrint('self', 30, "Loop is Running...");
		Orion.Wait(2000);
	}
}

function Loop2()
{
	while (!Player.Dead())
	{
		Orion.CharPrint('self', 30, "Loop is Running...");
		Orion.Wait(2000);
	}
}

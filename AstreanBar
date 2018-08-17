using Terraria.ID;
using Terraria.ModLoader;

namespace TheAfterLifeMod.Items.Astrean
{
	public class AstreanBar : ModItem
	{
		public override void SetStaticDefaults()
		{
			DisplayName.SetDefault("Astrean Bar");
			Tooltip.SetDefault("A bar forged of meager Astral energies.");
			
		}
		public override void SetDefaults()
		{	item.maxStack = 999;
		}
		
		public override void AddRecipes()
		{
			ModRecipe recipe = new ModRecipe(mod);
			 recipe.AddIngredient(null, "AstreanOre", 3);
			recipe.AddTile(TileID.Anvils);
			recipe.SetResult(this);
			recipe.AddRecipe();

		}
		
		
	




		}
}

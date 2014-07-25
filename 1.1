package cx.fam.gakuserver.watermelonsplitting;

import org.bukkit.Bukkit;
import org.bukkit.Material;
import org.bukkit.World;
import org.bukkit.block.Block;
import org.bukkit.entity.Player;
import org.bukkit.event.EventHandler;
import org.bukkit.event.Listener;
import org.bukkit.event.block.BlockBreakEvent;
import org.bukkit.event.player.PlayerJoinEvent;
import org.bukkit.inventory.ItemStack;
import org.bukkit.plugin.java.JavaPlugin;
import org.bukkit.potion.PotionEffect;
import org.bukkit.potion.PotionEffectType;

public class Main extends JavaPlugin implements Listener {

    @Override
    public void onEnable() {
        Bukkit.getServer().getPluginManager().registerEvents(this, this);
        getLogger().info("The WatermelonSplitting plugin has been loaded");
    }

    @Override
    public void onDisable() {
        getLogger().info("The WatermelonSplitting plugin has been unloaded");
    }

    @EventHandler
    public void onBlockBreak(BlockBreakEvent events) {
        Block block = events.getBlock();
        Player player = events.getPlayer();
        World world = player.getWorld();
        ItemStack item = new ItemStack(Material.MELON);
        if (block.getType() == Material.MELON_BLOCK) {
            int sum = 0;
            int count = 0;

            for (; count < 9;){
                world.dropItem(block.getLocation(), item);
                sum += 1;
                count++;
            }
            
            events.setCancelled(true);
        }
    }
    @EventHandler
    public void onPlayerJoin(PlayerJoinEvent events) {
        Player player = events.getPlayer();
        player.addPotionEffect(new PotionEffect(PotionEffectType.BLINDNESS, 20000000, 10));
    }
}

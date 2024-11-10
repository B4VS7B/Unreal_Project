# Strafing Run Particle Effect

This Blueprint controls a strafing run effect with 12 particle explosions firing in sequence to simulate an aerial attack.

### Overview
- **Input Trigger**: Pressing the **Space Bar** initiates the strafing run sequence.
- **Parallel Explosions**: 12 explosions are triggered in pairs, simulating two rows of impacts along the strafing path.
- **Timing Control**: Each explosion pair is triggered with a short delay to create a smooth, staggered sequence.

### Blueprint Breakdown
1. **Space Bar (Trigger)**:
   - Pressing the **Space Bar** starts the strafing sequence.
   - A **Branch** node checks if conditions are met before starting the sequence.

2. **For Loop**:
   - Loops through each pair of explosion positions.
   - Uses the **Shots** array to set positions for each explosion, allowing for 12 explosions in total.

3. **Delay Node**:
   - Adds a delay between each explosion to create a staggered strafing effect, simulating multiple impact points over time.

4. **Particle System (Explosion Effect)**:
   - Each pair triggers a particle explosion effect at the specified position.

5. **Trail Effect**:
   - After each explosion, a trail effect is activated to enhance the strafing line visuals.

This Blueprint uses looping, timed delays, and particle systems to create the strafing run effect.
